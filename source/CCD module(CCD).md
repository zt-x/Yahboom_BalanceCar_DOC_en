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
## CCD module (CCD)

* *

### Global variable
<table>
<thead class="table100-head">
<tr><th>Global variable</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>buf_CCD</td><td>char[20]</td><td>Used to store CCD data display</td></tr>
<tr><td>ADV</td><td>u16[128]</td><td>Store the voltage value of 128 pixels</td></tr>
<tr><td>CCD_Zhongzhi</td><td>u8</td><td>CCD median value</td></tr>
<tr><td>CCD_Yuzhi</td><td>u8</td><td>Annotation threshold</td></tr>
<tr><td>ADC_128X32</td><td>uint8_t[128]</td><td>Returns 128 pixel points ADV collection voltage values ​​array</td></tr>
</tbody>
</table>

### Macro definition
<table>
<thead class="table100-head">
<tr><th>Macro definition</th><th>value</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>TSL_SI</td><td>PBout(5)</td><td>SI signal</td></tr>
<tr><td>TSL_CLK</td><td>PBout(4)</td><td>CLK signal</td></tr>
<tr><td>CCD_SI_CLK</td><td>RCC_APB2Periph_GPIOB</td><td>The clock of the Si signal pin</td></tr>
<tr><td>CCD_SI_PIN</td><td>GPIO_Pin_5</td><td>Si signal's GPIO pin</td></tr>
<tr><td>CCD_SI_PORT</td><td>GPIOB</td><td>GPIO port of SI signal</td></tr>
<tr><td>CCD_CLK_CLK</td><td>RCC_APB2Periph_GPIOB</td><td>CLK signal pin clock</td></tr>
<tr><td>CCD_CLK_PIN</td><td>GPIO_Pin_4</td><td>CLK signal GPIO pin</td></tr>
<tr><td>CCD_CLK_PORT</td><td>GPIOB</td><td>CLK signal GPIO port</td></tr>
<tr><td>CCD_AO_CLK</td><td>RCC_APB2Periph_GPIOA</td><td>AO signal pin clock</td></tr>
<tr><td>CCD_AO_PIN</td><td>GPIO_Pin_4</td><td>AO signal's GPIO pin</td></tr>
<tr><td>CCD_AO_PORT</td><td>GPIOA</td><td>GPIO port of AO signal</td></tr>
<tr><td>CCD_ADC</td><td>ADC2</td><td>ADC used</td></tr>
<tr><td>CCD_ADC_CLK</td><td>RCC_APB2Periph_ADC2</td><td>ADC clock</td></tr>
<tr><td>CCD_ADC_CH</td><td>ADC_Channel_4</td><td>ADC channel</td></tr>
</tbody>
</table>


### method

#### ccd_Init(void)
Linear CCD initialization
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### Get_Adc_CCD(u8 ch)
AD sampling
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>ch</td><td>u8</td><td>ADC channel</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>AD conversion result</td><td>u16</td></tr>
</tbody>
</table>



#### Dly_us(void)
Delay function
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### RD_TSL(void)
CCD data collection
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### deal_data_ccd(void)
Start CCD collection and process output data
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### Find_CCD_Zhongzhi(void)
Linear CCD take medium value<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### CCD_Get_ADC_128X32(void)
Returns 128 pixel points ADV collection voltage values ​​and compress the amplitude to 128 \*32<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>uint8_t*</td><td>128 pointers to storage</td></tr>
</tbody>
</table>

#### OLED_Show_CCD_Image(uint8_t* p_img)
Display CCD images on OLED
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>p_img</td><td>uint8_t*</td><td>Pointing to image data</td></tr>
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

#### binToHex_low(u8 num)
Convert the binary number to low level, hexadecimal,
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>num</td><td>u8</td><td>Number to be converted</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>Low Sixteen Equipment Number</td><td>char</td></tr>
</tbody>
</table>

#### binToHex_high(u8 num)
Convert binary numbers to high level hexadic
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>num</td><td>u8</td><td>Number to be converted</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>High Sixteen -in -Publication Number</td><td>char</td></tr>
</tbody>
</table>

#### slove_data(void)
Processed the obtained data
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### sendToPc(void)
Send data to PC
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>
