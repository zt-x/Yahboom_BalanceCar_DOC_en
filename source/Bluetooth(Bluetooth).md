<style type="text/css">
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
            max-width: 800px;
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
    .code-container {
        background-color: #282c34;
        border-radius: 5px;
        padding: 15px;
        min-width: 600px;
        margin-bottom: 20px;
        overflow-x: auto;
        box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
    }
    pre {
        margin: 0;
    }
    code {
        font-family: 'Courier New', Courier, monospace !important;
        white-space: pre-wrap !important; /* Allows code to wrap in case it is too long */
        color: #ffffff !important;
        background-color: #282c34 !important;
        border: none !important;
        font-size: 100% !important;
    }
    .keyword {
        color: #c678dd; /* Purple */
        font-weight: bold;
    }
    .function {
        color: #61afef; /* blue */
    }
    .string {
        color: #98c379; /* green */
    }
    .include {
        color: #c678dd; /* Purple */
    }
    .header {
        color: #98c379; /* green */
    }
    .number {
        color: #d19a66; /* orange color */
    }

    .string {
        color: #56b6c2; /* blue */
    }

    .comment {
        color: #7f848e; /* grey */
    }
</style>
## Bluetooth(Bluetooth)

<div class="notice">
    <p>
        1.bsp_bluetooth.c The file is stored in the Bluetooth basic driver file
    </p>
    <p>
        2.app_bluetooth.c The file is stored in the file of the car application Bluetooth
    </p>
</div>



### Global variable

<table>
<thead class="table100-head">
<tr><th>Global variable</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>g_autoup</td><td>int</td><td>Automatically report</td></tr>
<tr><td>manydisplay</td><td>char[80]</td><td>Report data string</td></tr>
<tr><td>updata</td><td>char[80]</td><td>Store the final data</td></tr>
<tr><td>lspeed</td><td>char[10]</td><td>Left motor speed string</td></tr>
<tr><td>rspeed</td><td>char[10]</td><td>Right motor speed strings</td></tr>
<tr><td>daccel</td><td>char[10]</td><td>Acceleration string</td></tr>
<tr><td>dgyro</td><td>char[10]</td><td>Gyroscope data string</td></tr>
<tr><td>csb</td><td>char[10]</td><td>Ultrasonic distance string</td></tr>
<tr><td>vi</td><td>char[10]</td><td>Electric string</td></tr>
<tr><td>newLineReceived</td><td>u8</td><td>New Line Receive Label</td></tr>
<tr><td>num</td><td>int</td><td>Input string length</td></tr>
<tr><td>startBit</td><td>u8</td><td>Agreement starting</td></tr>
<tr><td>int9num</td><td>int</td><td>9th integer value</td></tr>
<tr><td>inputString</td><td>u8[80]</td><td>Receive input string</td></tr>
<tr><td>ProtocolString</td><td>u8[80]</td><td>Protocol string</td></tr>
<tr><td>g_newcarstate</td><td>enCarState</td><td>Car status</td></tr>
<tr><td>PID_Original</td><td>float[6]</td><td>PID initial value array</td></tr>
<tr><td>piddisplay</td><td>char[50]</td><td>PID display string</td></tr>
<tr><td>charkp</td><td>char[10]</td><td>Proportional gain KP string</td></tr>
<tr><td>charkd</td><td>char[10]</td><td>Microcar gain KD string</td></tr>
<tr><td>charksp</td><td>char[10]</td><td>Speed ​​ring kp string</td></tr>
<tr><td>charksi</td><td>char[10]</td><td>Speed ​​ring Ki string</td></tr>
<tr><td>charktp</td><td>char[10]</td><td>Steering ring kp string</td></tr>
<tr><td>charktd</td><td>char[10]</td><td>Steering ring kd string</td></tr>
</tbody>
</table>

### Macro definition
<table>
<thead class="table100-head">
<tr><th>Macro definition</th><th>value</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>run_car</td><td>'1'</td><td>Advance command</td></tr>
<tr><td>back_car</td><td>'2'</td><td>Back Command</td></tr>
<tr><td>left_car</td><td>'3'</td><td>Turn left command</td></tr>
<tr><td>right_car</td><td>'4'</td><td>Right turn command</td></tr>
<tr><td>stop_car</td><td>'0'</td><td>Stop command</td></tr>
</tbody>
</table>

### method

#### bluetooth_init(void)
Initialize Bluetooth Module
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### bluetooth_send_char(uint8_t ch)
Send a character
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>ch</td><td>uint8_t</td><td>The characters to be sent</td></tr>
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

#### UART5_Send_ArrayU8(uint8_t *BufferPtr, uint16_t Length)
Send a byte array
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>BufferPtr</td><td>uint8_t*</td><td>Data pointer to be sent</td></tr>
<tr><td>Length</td><td>uint16_t</td><td>Data length</td></tr>
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

#### USART5_Send_Byte(unsigned char byte)
Send a byte
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>byte</td><td>unsigned char</td><td>The bytes to be sent</td></tr>
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

#### bluetooth_send_string(char *s)
Send string
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>s</td><td>char*</td><td>String to be sent</td></tr>
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

#### Init_PID(void)
Initialize PID parameters
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### ResetPID(void)
PID parameters when resumed opening
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### deal_bluetooth(uint8_t rxbuf)
Process the receiving Bluetooth data
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>rxbuf</td><td>uint8_t</td><td>Received data</td></tr>
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

#### ProtocolCpyData(void)
Copy protocol data
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### Protocol(void)
Analysis protocol data
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### StringFind(const char *pSrc, const char *pDst)
Find sub -string
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>pSrc</td><td>const char*</td><td>Source string</td></tr>
<tr><td>pDst</td><td>const char*</td><td>Target string</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>Find starting index</td><td>int</td></tr>
</tbody>
</table>

#### CalcUpData(void)
Calculate and update the report data
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### SendAutoUp(void)
Report data automatically
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### ProtocolGetPID(void)
Get PID parameters
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>


### Example

<div class="code-container">
<pre><code>
<span class="include">#include </span><span class="string">"bsp_bluetooth.h"</span>
<span class="keyword">int </span><span class="function">main</span>() {
    bluetooth_init();
    bluetooth_send_string(<span class="string">"Hello Yahboom!\n"</span>);
    <span class="keyword">while</span>(1);
}
// <span class="comment">When Bluetooth receives the message, it will trigger the interruption</span>
<span class="keyword">void </span><span class="function">UART5_IRQHandler</span>(<span class="keyword">void</span>) {
    uint8_t Rx5_Temp;
    <span class="keyword">if</span> (USART_GetITStatus(UART5, USART_IT_RXNE) != RESET)
    {
        Rx5_Temp = USART_ReceiveData(UART5);
        bluetooth_send_char(Rx5_Temp);
    }
}
</code></pre>
</div>