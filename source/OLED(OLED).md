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
## OLED(OLED)

<div class="notice">
    <p>The driver library uses the more universal software (simulated) IIC method to drive the OLED, but the Yahboom Smart STM32 Balance Car V2 supports hardware IIC in the hardware circuit.</p>
    <p>The content of this chapter only introduces OLED related methods, and does not introduce the implementation of software IIC</p>
</div>

### method
#### void OLED_I2C_Init()

Initialize OLED module

#### void OLED_Clear()

Clear the screen

#### void OLED_Refresh()

Refresh the screen

#### void OLED_Draw_Stringg(char *str, uint8_t x, uint8_t y, bool clear, bool refresh)

Write into the string at the specified location

<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>str</td><td>char *</td><td>Want the string displayed by OLED</td></tr>
<tr><td>x</td><td>uint8_t</td><td>Draw the starting coordinates in the direction of string X</td></tr>
<tr><td>y</td><td>uint8_t</td><td>Draw the starting coordinates in the direction of the string y</td></tr>
<tr><td>clear</td><td>bool</td><td>Whether to empty the screen</td></tr>
<tr><td>refresh</td><td>uint8_t</td><td>Whether to screen immediately</td></tr>
<tr><td colspan="3">After drawing is completed, you need to call the refresh method to display</td></tr>
</tbody>
</table>


#### void OLED_Draw_Line(char *str, uint8_t line, bool clear, bool refresh)

Write a string in a designated line
/* Write a line of characters */

<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>str</td><td>char *</td><td>Want the string displayed by OLED</td></tr>
<tr><td>line</td><td>uint8_t</td><td>Display string in the first line</td></tr>
<tr><td>clear</td><td>bool</td><td>Whether to empty the screen</td></tr>
<tr><td>refresh</td><td>uint8_t</td><td>Whether to screen immediately</td></tr>
<tr><td colspan="3">The default line height is 10</td></tr>
</tbody>
</table>

<div class="notice">
    <p> The following method is provided for driving chip SSD1306, which can be used for more detailed drawing operations </p>
</div>



#### SSD1306_UpdateScreen()
The unit updates the OLED display content
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### SSD1306_ToggleInvert()
Switch the color reversal of the OLED display
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### SSD1306_Fill(SSD1306_COLOR_t Color)
Fill in the color of the screen
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>Color</td><td>SSD1306_COLOR_t</td><td>Fill color</td></tr>
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

#### SSD1306_DrawPixel(uint16_t x, uint16_t y, SSD1306_COLOR_t color)
Draw a pixel in the specified coordinate
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>x</td><td>uint16_t</td><td>X coordinate</td></tr>
<tr><td>y</td><td>uint16_t</td><td>y coordinate</td></tr>
<tr><td>color</td><td>SSD1306_COLOR_t</td><td>Pixel color</td></tr>
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

#### SSD1306_GotoXY(uint16_t x, uint16_t y)
Set the drawing coordinates of the next character
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>x</td><td>uint16_t</td><td>X coordinate</td></tr>
<tr><td>y</td><td>uint16_t</td><td>y coordinate</td></tr>
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

#### SSD1306_Putc(char ch, FontDef_t *Font, SSD1306_COLOR_t color)
Draw a single character
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>ch</td><td>char</td><td>Characters to be drawn</td></tr>
<tr><td>Font</td><td>FontDef_t*</td><td>Font structure used</td></tr>
<tr><td>color</td><td>SSD1306_COLOR_t</td><td>Character color</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>char</td></tr>
</tbody>
</table>

#### SSD1306_Puts(char *str, FontDef_t *Font, SSD1306_COLOR_t color)
Draw a string
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>str</td><td>char*</td><td>String to draw</td></tr>
<tr><td>Font</td><td>FontDef_t*</td><td>Font structure used</td></tr>
<tr><td>color</td><td>SSD1306_COLOR_t</td><td>String color</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>char</td></tr>
</tbody>
</table>

#### SSD1306_DrawLine(uint16_t x0, uint16_t y0, uint16_t x1, uint16_t y1, SSD1306_COLOR_t c)
Draw a line
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>x0</td><td>uint16_t</td><td>Starting point x coordinates</td></tr>
<tr><td>y0</td><td>uint16_t</td><td>Starting point y coordinate</td></tr>
<tr><td>x1</td><td>uint16_t</td><td>Ending point x coordinates</td></tr>
<tr><td>y1</td><td>uint16_t</td><td>Ending point y coordinates</td></tr>
<tr><td>c</td><td>SSD1306_COLOR_t</td><td>Line color</td></tr>
</tbody>
</table>
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>无</td><td>void</td></tr>
</tbody>
</table>

#### SSD1306_DrawRectangle(uint16_t x, uint16_t y, uint16_t w, uint16_t h, SSD1306_COLOR_t c)
Drawing rectangle
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>x</td><td>uint16_t</td><td>X coordinates in the upper left corner</td></tr>
<tr><td>y</td><td>uint16_t</td><td>Y coordinate in the upper left corner</td></tr>
<tr><td>w</td><td>uint16_t</td><td>Rectangular width</td></tr>
<tr><td>h</td><td>uint16_t</td><td>Rectangular height</td></tr>
<tr><td>c</td><td>SSD1306_COLOR_t</td><td>Rectangular color</td></tr>
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

#### SSD1306_DrawFilledRectangle(uint16_t x, uint16_t y, uint16_t w, uint16_t h, SSD1306_COLOR_t c)
Draw a rectangle
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>x</td><td>uint16_t</td><td>X coordinates in the upper left corner</td></tr>
<tr><td>y</td><td>uint16_t</td><td>Y coordinate in the upper left corner</td></tr>
<tr><td>w</td><td>uint16_t</td><td>Rectangular width</td></tr>
<tr><td>h</td><td>uint16_t</td><td>Rectangular height</td></tr>
<tr><td>c</td><td>SSD1306_COLOR_t</td><td>Rectangular color</td></tr>
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

#### SSD1306_DrawTriangle(uint16_t x1, uint16_t y1, uint16_t x2, uint16_t y2, uint16_t x3, uint16_t y3, SSD1306_COLOR_t color)
Draw a triangle
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>x1</td><td>uint16_t</td><td>The first point X coordinates</td></tr>
<tr><td>y1</td><td>uint16_t</td><td>The first point y coordinates</td></tr>
<tr><td>x2</td><td>uint16_t</td><td>The second point x coordinates</td></tr>
<tr><td>y2</td><td>uint16_t</td><td>The second point y coordinates</td></tr>
<tr><td>x3</td><td>uint16_t</td><td>Third point X coordinates</td></tr>
<tr><td>y3</td><td>uint16_t</td><td>The third point y coordinate</td></tr>
<tr><td>color</td><td>SSD1306_COLOR_t</td><td>Triangular color</td></tr>
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

#### SSD1306_DrawCircle(int16_t x0, int16_t y0, int16_t r, SSD1306_COLOR_t c)
Draw a circle
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>x0</td><td>int16_t</td><td>The x coordinate of the center of the circle</td></tr>
<tr><td>y0</td><td>int16_t</td><td>Y coordinate of the center of the circle</td></tr>
<tr><td>r</td><td>int16_t</td><td>radius</td></tr>
<tr><td>c</td><td>SSD1306_COLOR_t</td><td>Round color</td></tr>
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

#### SSD1306_DrawFilledCircle(int16_t x0, int16_t y0, int16_t r, SSD1306_COLOR_t c)
Draw a circle
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>x0</td><td>int16_t</td><td>The x coordinate of the center of the circle</td></tr>
<tr><td>y0</td><td>int16_t</td><td>Y coordinate of the center of the circle</td></tr>
<tr><td>r</td><td>int16_t</td><td>radius</td></tr>
<tr><td>c</td><td>SSD1306_COLOR_t</td><td>Fill in round colors</td></tr>
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

#### ssd1306_I2C_Init()
Initialize I2C interface
<table>
<thead class="table100-head">
<tr><th>Return value</th><th>type</th></tr>
</thead>
<tbody>
    <tr><td>none</td><td>void</td></tr>
</tbody>
</table>

#### ssd1306_I2C_Write(uint8_t address, uint8_t reg, uint8_t data)
Write data to the specified address and register
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>address</td><td>uint8_t</td><td>I2C device address</td></tr>
<tr><td>reg</td><td>uint8_t</td><td>Register address</td></tr>
<tr><td>data</td><td>uint8_t</td><td>Data to be written</td></tr>
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

#### ssd1306_I2C_WriteMulti(uint8_t address, uint8_t reg, uint8_t *data, uint16_t count)
Write multiple data to the specified address and register
<table>
<thead class="table100-head">
<tr><th>parameter</th><th>type</th><th>Annotation</th></tr>
</thead>
<tbody>
    <tr><td>address</td><td>uint8_t</td><td>I2C device address</td></tr>
<tr><td>reg</td><td>uint8_t</td><td>Register address</td></tr>
<tr><td>data</td><td>uint8_t*</td><td>Pointing to data pointer</td></tr>
<tr><td>count</td><td>uint16_t</td><td>Number of data to be written</td></tr>
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

### Example

<div class="code-container">
<pre>
<code>
<span class="include">#include </span><span class="string">"bsp_oled_i2c.h"</span>
<span class="include">#include </span><span class="string">"bsp_oled.h"</span>
<span class="keyword">int</span> <span class="keyword">main</span>() {
    <span class="function">OLED_I2C_Init</span>();
    <span class="function">OLED_Clear</span>();
    <span class="keyword">while</span>(<span class="number">1</span>) {
        <span class="function">OLED_DrawLine</span>(<span class="string">"Hello Yahboom!"</span>,<span class="number">1</span>, <span class="number">0</span>, true, true);
    }
    <span class="keyword">return</span> <span class="number">0</span>;
}
</code>
</pre>
</div>
