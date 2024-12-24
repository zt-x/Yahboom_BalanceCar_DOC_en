<style type="text/css">
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }

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
    .notice {
        background-color: #fff3cd; /* Light yellow background */
        color: #856404; /* Dark yellow font */
        border: 1px solid #ffeeba;
        padding: 15px;
        border-radius: 5px;
        margin: 20px 0 !important;
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
## Motor encoder(Encoder)

### Macro definition
The automatic loading value of the timer should not be greater than 65535 because the timer of the F103 is 16 -bit.<br>
<span class="include">#define ENCODER_TIM_PERIOD (u16)(65535)</span>

Calculate the parameters required for speed<br>
<span class="include">#define PI 3.14159265							//Pi circularity</span><br>
<span class="include">#define Control_Frequency  200.0	//Coder read frequency</span><br>
<span class="include">#define Diameter_67  67.0 				//Wheel diameter 67mm</span> <br>
<span class="include">#define EncoderMultiples   4.0 		//Coder multiple frequency frequency</span><br>
<span class="include">#define Encoder_precision  11.0 	//Coder accuracy 11 line</span><br>
<span class="include">#define Reduction_Ratio  30.0			//Death ratio 30</span><br>
<span class="include">#define Perimeter  210.4867 			//Week length, unit mm</span><br>

<div class="notice">
    <p>Control_Frequency=200 It means that the value of Read_encoder () is 5ms </p>
</div>

<div class="code-container">
<pre>
<code>
<br>
ID of left and right wheels<br>
typedef enum {<br>
    MOTOR_ID_ML = 0,<br>
    MOTOR_ID_MR,<br>
    MAX_MOTOR<br>
} Motor_ID;<br>
<br>
</code>
</pre>
</div>

### method

<div class="notice">
    <p>If you want to use the motor MOTOR, make sure that the function of the initialization motor must be called before the initialized encoder timer <b> </b> !!</p>
</div>

#### Encoder_Init_TIM3(void)
Initialize TIM3 timer
<table>
<thead class="table100-head">
    <tr>
        <th>Setting project</th>
        <th>Set value</th></tr>
</thead>
<tbody>
    <tr><td>Prescaler</td>
        <td>0</td>
    </tr>
    <tr>
        <td>Automatic reinstatement</td>
        <td>ENCODER_TIM_PERIOD(The specific value needs to be viewed code)</td>
    </tr>
    <tr>
        <td>Clock frequency</td>
        <td>Indomitable (TIM_CKD_DIV1)</td>
    </tr>
    <tr>
        <td>Count mode</td>
        <td>Counting up (TIM_CounterMode_Up)</td>
    </tr>
    <tr>
        <td>Enter the capture filter</td>
        <td>10</td>
    </tr>
    <tr>
        <td>GPIO pin</td>
        <td>GPIO_Pin_6 和 GPIO_Pin_7</td>
    </tr>
    <tr>
        <td>GPIO mode</td>
        <td>Floating input (GPIO_Mode_IN_FLOATING)</td>
    </tr>
    <tr>
        <td>Timer 3 clock enable</td>
        <td>Clock of the timer 3</td>
    </tr>
    <tr>
        <td>PA port clock enable</td>
        <td>Make the PA port clock</td>
    </tr>
    <tr>
        <td>Encoder mode</td>
        <td>Coder mode 3 (TIM_EncoderMode_TI12)</td>
    </tr>
    <tr>
        <td>Extract the catch</td>
        <td>Rising edge trigger (TIM_ICPolarity_Rising)</td>
    </tr>
    <tr>
        <td>TIM update logo clearance</td>
        <td>Clear Tim's update logo</td>
    </tr>
    <tr>
        <td>TIM update interrupt enable enable</td>
        <td>Make TIM update interruption</td>
    </tr>
</tbody>
</table>

#### Encoder_Init_TIM4(void)
Initialize TIM4 timer
<table>
<thead class="table100-head">
    <tr>
        <th>Setting project</th>
        <th>Set value</th></tr>
</thead>
<tbody>
    <tr><td>Timer structure</td>
        <td>TIM_TimeBaseInitTypeDef TIM_TimeBaseStructure</td>
    </tr>
    <tr>
        <td>Enter the capture structure</td>
        <td>TIM_ICInitTypeDef TIM_ICInitStructure</td>
    </tr>
    <tr>
        <td>GPIO initialization structure</td>
        <td>GPIO_InitTypeDef GPIO_InitStructure</td>
    </tr>
    <tr>
        <td>Timer 4 clock enable</td>
        <td>Clock with a clock with timer 4 (RCC_APB1PeriphClockCmd(RCC_APB1Periph_TIM4, ENABLE))</td>
    </tr>
    <tr>
        <td>PB port clock enable</td>
        <td>Make the PB port clock (RCC_APB2PeriphClockCmd(RCC_APB2Periph_GPIOB, ENABLE))</td>
    </tr>
    <tr>
        <td>GPIO pin configuration</td>
        <td>GPIO_Pin_6 | GPIO_Pin_7</td>
    </tr>
    <tr>
        <td>GPIO mode</td>
        <td>Floating input (GPIO_Mode_IN_FLOATING)</td>
    </tr>
    <tr>
        <td>GPIO initialization</td>
        <td>Initialize GPIOB according to the setting parameter (GPIO_Init(GPIOB, &GPIO_InitStructure))</td>
    </tr>
    <tr>
        <td>Initialization of timer basic configuration</td>
        <td>TIM_TimeBaseStructInit(&TIM_TimeBaseStructure)</td>
    </tr>
    <tr>
        <td>Prescaler</td>
        <td>0x0</td>
    </tr>
    <tr>
        <td>The counter automatic reinstallation value</td>
        <td>ENCODER_TIM_PERIOD</td>
    </tr>
    <tr>
        <td>Clock frequency</td>
        <td>Indomitable (TIM_CKD_DIV1)</td>
    </tr>
    <tr>
        <td>Count mode</td>
        <td>Counting up (TIM_CounterMode_Up)</td>
    </tr>
    <tr>
        <td>Timer initialization</td>
        <td>TIM_TimeBaseInit(TIM4, &TIM_TimeBaseStructure)</td>
    </tr>
    <tr>
        <td>Code interface configuration</td>
        <td>Use the encoder mode 3 (TIM_EncoderInterfaceConfig(TIM4, TIM_EncoderMode_TI12, TIM_ICPolarity_Rising, TIM_ICPolarity_Rising))</td>
    </tr>
    <tr>
        <td>Input capture structure initialization</td>
        <td>TIM_ICStructInit(&TIM_ICInitStructure)</td>
    </tr>
    <tr>
        <td>Enter the capture filter</td>
        <td>10</td>
    </tr>
    <tr>
        <td>Input capture initialization</td>
        <td>TIM_ICInit(TIM4, &TIM_ICInitStructure)</td>
    </tr>
    <tr>
        <td>TIM update logo clearance</td>
        <td>Clear Tim's update logo (TIM_ClearFlag(TIM4, TIM_FLAG_Update))</td>
    </tr>
    <tr>
        <td>TIM update interrupt enable enable</td>
        <td>Make TIM update interruption (TIM_ITConfig(TIM4, TIM_IT_Update, ENABLE))</td>
    </tr>
</tbody>
</table>


#### Read_Encoder(Motor_ID MYTIMX)
Read the encoder count of unit time

<div class="notice">
    <p>
        Read_Encoder() Reading from the last time calling_encoder () to this time calling_encoder (), the number of encoders during the period
    </p>
    <p>
        In order to calculate the speed, Read_encoder () needs to be called at a fixed time interval
    </p>
</div>


<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>MYTIMX</td><td>Motor_ID</td><td>Choose a motor to read</td></tr>
<tr><td colspan="3">
Motor_ID Optional parameter MOTOR_ID_ML/MOTOR_ID_MR</td></tr>
</tbody>
</table>

<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>Encoder count</td><td>int</td></tr>
</tbody>
</table>



#### Get_Velocity_From_Encoder(int encoder_left, int encoder_right);
Return to the speed of the left and right wheels, the unit is mm/s

<div class="notice">
    <p>
        This function defaults to 5ms as a speed measurement cycle, corresponding to the control_frequency = 200 (t = 1/f) in the definition of the macro definition
    </p>
</div>


<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>encoder_left</td><td>int</td><td>Left motor encoder value</td></tr>
<tr><td>encoder_right</td><td>int</td><td>Right motor encoder value</td></tr>
</tbody>
</table>

<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>velocities</td><td>float*</td></tr>
<tr><td colspan="2">The return value is a speed array <br> Velocities [0] is the speed of the left motor <br> Velocities [1] is the right motor speed, the unit is MM/S</td></tr>
</tbody>
</table>



#### TIM3_IRQHandler(void);
Timer 3 interrupt processing function

#### TIM4_IRQHandler(void);
Timer 4 interrupt processing function

### 使用示例

<div class="code-container">
<pre>
<code>
// <span class="comment"> Introduction part of the code is omitted </span>
<span class="keyword">int</span> <span class="keyword">main</span>() {
    <span class="function">Encoder_Init_TIM3</span>();
    <span class="function">Encoder_Init_TIM4</span>();
    <span class="keyword">int</span> left_count = <span class="number">0</span>;
    <span class="keyword">int</span> right_count = <span class="number">0</span>;
    <span class="keyword">while</span>(<span class="number">1</span>) {
        // <span class="comment"> Take 5ms as the speed measurement cycle, corresponding to the control_frequency = 200 (t = 1/f) in the definition of macro definition</span>
        <span class="function">delay_ms</span>(5);
        left_count <span class="keyword">+=</span> <span class="function">Read_Encoder</span>(<span class="string">MOTOR_ID_ML</span>);
        right_count <span class="keyword">+=</span> <span class="function">Read_Encoder</span>(<span class="string">MOTOR_ID_MR</span>);
        <span class="function">printf</span>(<span class="string">"L: %d, R: %d\n"</span>, left_count, right_count);
    }
    <span class="keyword">return</span> <span class="number">0</span>;
}
</code>
</pre>
</div>
