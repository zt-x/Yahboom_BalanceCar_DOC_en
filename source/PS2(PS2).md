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
## PS2(PS2) 
* *

### Global variable
<table>
<thead class="table100-head">
<tr><th>Global variable</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>Handkey</td><td>u16</td><td>Key value read temporary storage</td></tr>
<tr><td>Comd</td><td>u8[2]</td><td>Start command array</td></tr>
<tr><td>Data</td><td>u8[9]</td><td>Data storage array</td></tr>
<tr><td>MASK</td><td>u16[16]</td><td>Key to cover the array</td></tr>
</tbody>
</table>

### Macro definition
<table>
<thead class="table100-head">
<tr><th>Macro definition</th><th>value</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>PS_RCC_DI</td><td>RCC_APB2Periph_GPIOB</td><td>Data input DI pin clock</td></tr>
<tr><td>PS_RCC_DO</td><td>RCC_APB2Periph_GPIOB</td><td>The clock of the data output DO pin</td></tr>
<tr><td>PS_RCC_CS</td><td>RCC_APB2Periph_GPIOB</td><td>Clock clock selection CS pin</td></tr>
<tr><td>PS_RCC_CLK</td><td>RCC_APB2Periph_GPIOB</td><td>Clock clock clock</td></tr>
<tr><td>PS_PIN_DI</td><td>GPIO_Pin_14</td><td>Data input DI football</td></tr>
<tr><td>PS_PIN_DO</td><td>GPIO_Pin_15</td><td>Data output do foot</td></tr>
<tr><td>PS_PIN_CS</td><td>GPIO_Pin_12</td><td>CS pin</td></tr>
<tr><td>PS_PIN_CLK</td><td>GPIO_Pin_13</td><td>Clock CLK pin</td></tr>
<tr><td>PS_PORT_DI</td><td>GPIOB</td><td>GPIO port of di pin</td></tr>
<tr><td>PS_PORT_DO</td><td>GPIOB</td><td>GPIO port of Do pin</td></tr>
<tr><td>PS_PORT_CS</td><td>GPIOB</td><td>GPIO port of CS pin</td></tr>
<tr><td>PS_PORT_CLK</td><td>GPIOB</td><td>GPIO port of CLK pin</td></tr>
<tr><td>DI</td><td>PBin(14)</td><td>Data input</td></tr>
<tr><td>DO_H</td><td>PBout(15)=1</td><td>High command position</td></tr>
<tr><td>DO_L</td><td>PBout(15)=0</td><td>Low command position</td></tr>
<tr><td>CS_H</td><td>PBout(12)=1</td><td>CS pulled high</td></tr>
<tr><td>CS_L</td><td>PBout(12)=0</td><td>CS pulled low</td></tr>
<tr><td>CLK_H</td><td>PBout(13)=1</td><td>Clock high</td></tr>
<tr><td>CLK_L</td><td>PBout(13)=0</td><td>Clock low</td></tr>
<tr><td>PSB_*</td><td>Corresponding key value</td><td>The constant definition of various keys</td></tr>
</tbody>
</table>


### method

#### PS2_Init(void)
PS2 receiver module initialization
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### PS2_Cmd(u8 CMD)
Send command to the handle
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>CMD</td><td>u8</td><td>Order to be sent</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>noneone</td><td>void</td></tr>
</tbody>
</table>

#### PS2_RedLight(void)
Determine whether it is a red light mode
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>0</td><td>u8</td><td>Red light mode</td></tr>
<tr><td>1</td><td>u8</td><td>Other modes</td></tr>
</tbody>
</table>

#### PS2_ReadData(void)
Read the handle data
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### PS2_DataKey(void)
Read the key value
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>Key value</td><td>u8</td></tr>
</tbody>
</table>

#### PS2_AnologData(u8 button)
The analog of getting the joystick
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>button</td><td>u8</td><td>The joystick button to be read</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>Simulation</td><td>u8</td></tr>
</tbody>
</table>

#### PS2_ClearData(void)
Clear data buffer
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### PS2_Vibration(u8 motor1, u8 motor2)
Set the handle vibration
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>motor1</td><td>u8</td><td>Small vibration motor on the right (0x00 level, other opening)</td></tr>
<tr><td>motor2</td><td>u8</td><td>The left large vibration motor (0x40 ~ 0xff opened, the larger the value, the larger the vibration)</td></tr>
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

#### PS2_ShortPoll(void)
Inquiry
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### PS2_EnterConfing(void)
Enter the configuration mode
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### PS2_TurnOnAnalogMode(void)
Send analog mode settings
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### PS2_VibrationMode(void)
Set up vibration mode
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### PS2_ExitConfing(void)
Complete and save configuration
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### PS2_SetInit(void)
Controller configuration initialization
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### PS2_Data_Show(void)
Key value test and output function
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>





