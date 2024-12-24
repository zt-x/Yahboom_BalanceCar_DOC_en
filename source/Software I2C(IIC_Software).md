<style type="text/css">
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }

        .notice {
            background-color: #fff3cd; /* Light yellow background */
            color: #856404; /* Dark yellow font */
            border: 1px solid #ffeeba;
            padding: 15px;
            border-radius: 5px;
            margin: 20px 0 !important;
        }

        .notice h2 {
            margin: 0 0 10px;
        }

        .notice p {
            margin: 0;
        }
    /* TABLE TEST */
    .container-table100 {
    width: 100%;
    min-height: 100vh;
    background: #c850c0;
    background: -webkit-linear-gradient(45deg, #4158d0, #c850c0);
    background: -o-linear-gradient(45deg, #4158d0, #c850c0);
    background: -moz-linear-gradient(45deg, #4158d0, #c850c0);
    background: linear-gradient(45deg, #4158d0, #c850c0);

    display: -webkit-box;
    display: -webkit-flex;
    display: -moz-box;
    display: -ms-flexbox;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    padding: 33px 30px;
    }

    .wrap-table100 {
    width: 1170px;
    }

    table {
    border-spacing: 1;
    border-collapse: collapse;
    background: white;
    border-radius: 10px;
    overflow: hidden;
    width: 100%;
    position: relative;
    }
    table * {
    position: relative;
    }
    table td, table th {
    padding-left: 8px;
    }
    table thead tr {
    height: 60px;
    background: #36304a;
    }
    table tbody tr {
    height: 50px;
    }
    table tbody tr:last-child {
    border: 0;
    }
    table td, table th {
    text-align: left;
    }
    table td.l, table th.l {
    text-align: right;
    }
    table td.c, table th.c {
    text-align: center;
    }
    table td.r, table th.r {
    text-align: center;
    }


    .table100-head th{
    font-family: OpenSans-Regular;
    font-size: 18px;
    color: #fff;
    line-height: 1.2;
    font-weight: unset;
    }

    tbody tr:nth-child(even) {
    background-color: #f5f5f5;
    }

    tbody tr {
    font-family: OpenSans-Regular;
    font-size: 15px;
    color: #808080;
    line-height: 1.2;
    font-weight: unset;
    }

    tbody tr:hover {
    color: #555555;
    background-color: #f5f5f5;
    cursor: pointer;
    }

    .column1 {
    width: 260px;
    padding-left: 40px;
    }

    .column2 {
    width: 160px;
    }

    .column3 {
    width: 245px;
    }

    .column4 {
    width: 110px;
    text-align: right;
    }

    .column5 {
    width: 170px;
    text-align: right;
    }

    .column6 {
    width: 222px;
    text-align: right;
    padding-right: 62px;
    }


    @media screen and (max-width: 992px) {
    table {
        display: block;
    }
    table > *, table tr, table td, table th {
        display: block;
    }
    table thead {
        display: none;
    }
    table tbody tr {
        height: auto;
        padding: 37px 0;
    }
    table tbody tr td {
        padding-left: 40% !important;
        margin-bottom: 24px;
    }
    table tbody tr td:last-child {
        margin-bottom: 0;
    }
    table tbody tr td:before {
        font-family: OpenSans-Regular;
        font-size: 14px;
        color: #999999;
        line-height: 1.2;
        font-weight: unset;
        position: absolute;
        width: 40%;
        left: 30px;
        top: 0;
    }
    table tbody tr td:nth-child(1):before {
        content: "Date";
    }
    table tbody tr td:nth-child(2):before {
        content: "Order ID";
    }
    table tbody tr td:nth-child(3):before {
        content: "Name";
    }
    table tbody tr td:nth-child(4):before {
        content: "Price";
    }
    table tbody tr td:nth-child(5):before {
        content: "Quantity";
    }
    table tbody tr td:nth-child(6):before {
        content: "Total";
    }

    .column4,
    .column5,
    .column6 {
        text-align: left;
    }

    .column4,
    .column5,
    .column6,
    .column1,
    .column2,
    .column3 {
        width: 100%;
    }

    tbody tr {
        font-size: 14px;
    }
    }

    @media (max-width: 576px) {
    .container-table100 {
        padding-left: 15px;
        padding-right: 15px;
    }
    }
    /* TABLE TEST END */

    table {font-size:12px;max-width:80%;min-width:30%;border-width: 0px;border-collapse: collapse;margin-bottom: 20px;box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;}
    th {font-size:12px;border-width: 1px;padding: 8px;text-align:left;}
        td {font-size:12px;border-width: 1px;padding: 8px; vertical-align: middle;font-size: 16px;}
</style>
## Software I2C(IIC_Software)

<div class="notice">
    <p>The driver library is located in the <br> MPU6050/IIC_SOFTWARE </br> directory, which is only used in the car to make communication support for MPU6050</p>
</div>


### method
#### IIC_MPU6050_Init()
IIC pin of MPU6050 initialization
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### IIC_Start()
Simulation IIC starting signal
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>1</td><td>int</td></tr>
</tbody>
</table>

#### IIC_Stop()
Simulation IIC end signal
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### IIC_Wait_Ack()
IIC waiting to be answered
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>0: No response; 1: Receive the answer</td><td>int</td></tr>
</tbody>
</table>

#### IIC_Ack()
IIC response
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### IIC_NAck()
IIC No Response
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### IIC_Send_Byte(u8 txd)
IIC send a byte
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>txd</td><td>u8</td><td>The byte data sent</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### i2cWrite(uint8_t addr, uint8_t reg, uint8_t len, uint8_t *data)
IIC writing data to the register
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>addr</td><td>uint8_t</td><td>Device address</td></tr>
<tr><td>reg</td><td>uint8_t</td><td>Register address</td></tr>
<tr><td>len</td><td>uint8_t</td><td>Number of bytes</td></tr>
<tr><td>data</td><td>uint8_t*</td><td>data</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>0: Successfully write; 1: Unsuccessful writing</td><td>int</td></tr>
</tbody>
</table>

#### i2cRead(uint8_t addr, uint8_t reg, uint8_t len, uint8_t *buf)
IIC reader data
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>addr</td><td>uint8_t</td><td>Device address</td></tr>
<tr><td>reg</td><td>uint8_t</td><td>Register address</td></tr>
<tr><td>len</td><td>uint8_t</td><td>Number of bytes</td></tr>
<tr><td>buf</td><td>uint8_t*</td><td>Read data cache</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>0: Read it successfully; 1: No successfully read out</td><td>int</td></tr>
</tbody>
</table>

#### IIC_Read_Byte(unsigned char ack)
IIC read a byte
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>ack</td><td>unsigned char</td><td>Whether to send a response signal; 1: Send; 0: Do not send</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>Receive: Reading data</td><td>u8</td></tr>
</tbody>
</table>

#### I2C_ReadOneByte(unsigned char I2C_Addr, unsigned char addr)
Read a value of specified device specified register
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>I2C_Addr</td><td>unsigned char</td><td>Device IIC address</td></tr>
<tr><td>addr</td><td>unsigned char</td><td>Register address</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>Res: read data</td><td>unsigned char</td></tr>
</tbody>
</table>

#### IICreadBytes(u8 dev, u8 reg, u8 length, u8 *data)
IIC continuous reading data
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>dev</td><td>u8</td><td>Target device IIC address</td></tr>
<tr><td>reg</td><td>u8</td><td>Register address</td></tr>
<tr><td>length</td><td>u8</td><td>Number of bytes</td></tr>
<tr><td>data</td><td>u8*</td><td>Reading data will be stored</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>Count: Number of bytes read -1</td><td>u8</td></tr>
</tbody>
</table>

#### IICwriteBytes(u8 dev, u8 reg, u8 length, u8* data)
Write multiple bytes into the specified device specified register
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>dev</td><td>u8</td><td>Target device address</td></tr>
<tr><td>reg</td><td>u8</td><td>Register address</td></tr>
<tr><td>length</td><td>u8</td><td>Number of bytes to be written</td></tr>
<tr><td>data</td><td>u8*</td><td>The first address of the data to be written</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>1: Is it successful?</td><td>u8</td></tr>
</tbody>
</table>

#### IICreadByte(u8 dev, u8 reg, u8 *data)
Read a value of specified device specified register
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>dev</td><td>u8</td><td>Target device address</td></tr>
<tr><td>reg</td><td>u8</td><td>Register address</td></tr>
<tr><td>data</td><td>u8*</td><td>Reading data will be stored</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>1: Return whether it is successful</td><td>u8</td></tr>
</tbody>
</table>

#### IICwriteByte(unsigned char dev, unsigned char reg, unsigned char data)
Write a device specified by the designated device to specify a byte of the register
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>dev</td><td>unsigned char</td><td>Target device address</td></tr>
<tr><td>reg</td><td>unsigned char</td><td>Register address</td></tr>
<tr><td>data</td><td>unsigned char</td><td>The byte data sent</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>1: Return whether it is successful</td><td>u8</td></tr>
</tbody>
</table>

#### IICwriteBits(u8 dev, u8 reg, u8 bitStart, u8 length, u8 data)
Reading, modifying, and writing a specified device specifies multiple bits in a byte of the register
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>dev</td><td>u8</td><td>Target device address</td></tr>
<tr><td>reg</td><td>u8</td><td>Register address</td></tr>
<tr><td>bitStart</td><td>u8</td><td>The starting position of the target byte</td></tr>
<tr><td>length</td><td>u8</td><td>The number of the target byte</td></tr>
<tr><td>data</td><td>u8</td><td>Stock the value of changing the target byte position</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>1: Success; 0: Fail</td><td>u8</td></tr>
</tbody>
</table>

#### IICwriteBit(u8 dev, u8 reg, u8 bitNum, u8 data)
Read, modify, and write a specified device to specify 1 digit in a byte of the register
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>dev</td><td>u8</td><td>Target device address</td></tr>
<tr><td>reg</td><td>u8</td><td>Register address</td></tr>
<tr><td>bitNum</td><td>u8</td><td>To modify the bitnum bit of the target byte</td></tr>
<tr><td>data</td><td>u8</td><td>At the time of 0, the target level will be clear, otherwise it will be placed</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>1: Success; 0: Fail</td><td>u8</td></tr>
</tbody>
</table>

