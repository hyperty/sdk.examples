# Browser compatibility report
## Background
According to the needs and feedback of the customers, our <a href="https://developers.altizure.com/demo"> demo</a> should have the ability to run on different browsers, so we did some tests on the compatibility of our demo.

The following tables are the statistics of browser market share of world and China in June 2018.
<p>Global browser market share <a href="https://netmarketshare.com/browser-market-share.aspx?options=%7B%22filter%22%3A%7B%22%24and%22%3A%5B%7B%22deviceType%22%3A%7B%22%24in%22%3A%5B%22Desktop%2Flaptop%22%5D%7D%7D%5D%7D%2C%22dateLabel%22%3A%22Trend%22%2C%22attributes%22%3A%22share%22%2C%22group%22%3A%22browser%22%2C%22sort%22%3A%7B%22share%22%3A-1%7D%2C%22id%22%3A%22browsersDesktop%22%2C%22dateInterval%22%3A%22Monthly%22%2C%22dateStart%22%3A%222017-07%22%2C%22dateEnd%22%3A%222018-06%22%2C%22segments%22%3A%22-1000%22%7D"> link</a></p>
<table>
<thead>
<tr>
<th>Browser</th>
<th>Chrome</th>
<th>IE</th>
<th>Firefox</th>
<th>Edge</th>
<th>Safari</th>
<th>Sogou</th>
<th>QQ</th>
<th>Opera</th>
<th>UC</th>
</tr>
</thead>
<tbody>
<tr>
<td>Share</td>
<td>61.20%</td>
<td>12.14%</td>
<td>11.27%</td>
<td>4.19%</td>
<td>3.76%</td>
<td>1.65%</td>
<td>1.52%</td>
<td>1.52%</td>
<td>0.72%</td>
</tbody>
</table>

<p>China browser market share <a href="http://tongji.baidu.com/data/browser"> link</a></p>
<table>
<thead>
<tr>
<th>Browser</th>
<th>Chrome</th>
<th>IE9.0</th>
<th>QQ</th>
<th>IE8.0</th>
<th>2345</th>
<th>IE11.0</th>
<th>Sogou</th>
<th>IE7.0</th>
<th>Firefox</th>
</tr>
</thead>
<tbody>
<tr>
<td>Share</td>
<td>46.93%</td>
<td>9.02%</td>
<td>6.07%</td>
<td>5.74%</td>
<td>5.58%</td>
<td>5.44%</td>
<td>4.47%</td>
<td>2.39%</td>
<td>2.37%</td>
</tbody>
</table>


Basic on the tables above, 11 browsers with the highest market share were selected for compatibility testing.

Among the multiple versions of IE, we only tested and fixed the compatibility issues with IE11.0.

## Browser compatibility
<table border="1" bordercolor="white">
<thead>
<tr>
<th style="text-align:center" ></th>
<th style="text-align:center">Chrome</th>
<th style="text-align:center">IE11.0</th>
<th style="text-align:center">Firefox</th>
<th style="text-align:center">Edge</th>
<th style="text-align:center">Safari</th>
<th style="text-align:center">UC</th>
<th style="text-align:center">Opera</th>
<th style="text-align:center">QQ</th>
<th style="text-align:center">Sogou</th>
<th style="text-align:center">360</th>
<th style="text-align:center">2345</th>
</tr>
</thead>
<tbody>
<tr>
<!--use base64 function to store browser icon-->
<td></td>
<td style="text-align:center" width="30pix"><img src="data:image/ico;base64,AAABAAEAICAAAAEAIACoEAAAFgAAACgAAAAgAAAAQAAAAAEAIAAAAAAAABAAABILAAASCwAAAAAAAAAAAAD///////////////////////////////////////////////////////////n5+f/e3t7/y8vL//Ly8v+ysrL/pKSk/7Kysv+/v7//5OTk//r6+v///////////////////////////////////////////////////////////////////////////////////////////////////////v7+/+Xl5f+kpKT/UlJS/yYmJv8iIiL/w8PD/3l5ef8FBQX/CQkJ/w8PD/8sLCz/WFhY/6ysrP/r6+v//////////////////////////////////////////////////////////////////////////////////////+zs7P+RkZH/LS0t/wUFBf8AAAD/AAAA/wAAAP9WVlb/z8/P/yUlJf8AAAD/AAAA/wAAAP8AAAD/BgYG/zU1Nf+ioqL/8/Pz///////////////////////////////////////////////////////////////////////Dw8P/QUFB/wQEBP8AAAD/AAAA/wAAAP8AAAD/AAAA/wkJCf+kpKT/j4+P/wQEBP8AAAD/AAAA/wAAAP8AAAD/AAAA/wgICP9QUFD/0dHR///////////////////////////////////////////////////////+/v7/qamp/x4eHv8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/zc3N//V1dX/Pz8//wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8tLS3/vr6+/////////////////////////////////////////////////6mpqf8WFhb/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AgIC/46Ojv+vr6//DAwM/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8kJCT/v7+////////////////////////////////////////Dw8P/Hx8f/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/ISEh/8vL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m//FxcX/KCgo/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/d3d3////////////q6ur/wYGBv8AAAD/Ly8v/9PT0/9QUFD/AAAA/wAAAP8AAAD/AAAA/zk5Of+5ubn/y8vL/5eXl/9zc3P/eHh4/52dnf/b29v/8PDw/5WVlf9oaGj/ampq/2pqav9qamr/ampq/2pqav9qamr/ampq/2xsbP/T09P////////////p6en/NTU1/wMDA/+goKD/nJyc/wcHB/8AAAD/AAAA/wAAAP8AAAD/AAAA/xEREf9TU1P/jo6O/7W1tf+8vLz/vb29/7u7u/+4uLj/uLi4/7q6uv+6urr/urq6/7q6uv+6urr/urq6/7q6uv+5ubn/3d3d//////////////////////+dnZ3/WVlZ/87Ozv8uLi7/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/BQUF/wcHB/8HBwf/BwcH/wcHB/8HBwf/BwcH/wcHB/8HBwf/BwcH/wcHB/8HBwf/BgYG/xYWFv+9vb3///////////////////////Ly8v/h4eH/dXV1/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/Z2dn//r6+v////////////////////////////Pz8/9DQ0P/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/z09Pf/f39///////////////////////////////////////729vf8jIyP/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8yMjL/zc3N/////////////////////////////////////////////////76+vv8vLy//AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/PDw8/83Nzf///////////////////////////////////////////////////////////9TU1P9WVlb/CgoK/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/Dw8P/2ZmZv/f39////////////////////////////////////////////////////////////////////////b29v+srKz/Pj4+/wkJCf8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/DQ0N/0pKSv+4uLj/+fn5///////////////////////////////////////////////////////////////////////////////////////v7+//urq6/2tra/86Ojr/Gxsb/wwMDP8LCwv/CwsL/w0NDf8eHh7/PT09/3Z2dv/Dw8P/8/Pz/////////////////////////////////////////////////////////////////////////////////////////////////////////////Pz8//Dw8P/R0dH/ubm5/7e3t/+3t7f/u7u7/9bW1v/y8vL//f39////////////////////////////////////////////////////////////AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA="></td>
<td style="text-align:center" width="30pix"><img src="data:image/ico;base64,AAABAAEAICAAAAEAIACoEAAAFgAAACgAAAAgAAAAQAAAAAEAIAAAAAAAABAAAHQSAAB0EgAAAAAAAAAAAAD//////f39///////////////////////////////////////9/f3//Pz8//7+/v/7+/v//f39///////////////////////////////////////8/Pz//Pz8//7+/v/////////////////////////////////////////////////+/v7/rq6u/0hISP8tLS3/MTEx/zk5Of93d3f/zs7O////////////////////////////8fHx/87Ozv/Hx8f/xsbG/8PDw//Q0ND/+/v7/////////////v7+//z8/P///////////////////////////////////////////3Nzc/8AAAD/AAAA/0dHR/+ysrL/ubm5/3R0dP8lJSX/PT09/7y8vP/u7u7/p6en/0VFRf8YGBj/AAAA/wAAAP8AAAD/AAAA/wICAv8kJCT/VlZW/7u7u//7+/v///////39/f/+/v7////////////////////////////Jycn/BwcH/wAAAP9bW1v///////7+/v/+/v7//v7+//////+ZmZn/AgIC/xcXF/8AAAD/AAAA/wAAAP8BAQH/AQEB/wEBAf8BAQH/AQEB/wAAAP8BAQH/AAAA/y0tLf+1tbX///////39/f/9/f3//////////////////////4mJif8AAAD/AQEB/83Nzf//////+vr6//r6+v//////6Ojo/09PT/8AAAD/AQEB/wMDA/8DAwP/AQEB/wAAAP8AAAD/AAAA/wAAAP8AAAD/AgIC/wMDA/8CAgL/AQEB/wAAAP9cXFz/9/f3///////9/f3/////////////////d3d3/wAAAP8ZGRn/7Ozs///////7+/v//////87Ozv8bGxv/AAAA/wICAv8BAQH/AAAA/wAAAP8AAAD/AAAA/wICAv8DAwP/AgIC/wAAAP8AAAD/AAAA/wAAAP8CAgL/BAQE/wAAAP87Ozv/7u7u///////+/v7///////////+Ojo7/AAAA/xAQEP/i4uL////////////f39//Gxsb/wAAAP8EBAT/AAAA/wAAAP8AAAD/AAAA/wMDA/8CAgL/AAAA/wAAAP8AAAD/AQEB/wMDA/8BAQH/AAAA/wAAAP8AAAD/BQUF/wAAAP87Ozv/9/f3///////+/v7//////7S0tP8AAAD/AAAA/8LCwv//////9vb2/zs7O/8AAAD/BAQE/wAAAP8AAAD/AAAA/wEBAf8CAgL/AAAA/wAAAP8eHh7/ODg4/yoqKv8DAwP/AAAA/wICAv8BAQH/AAAA/wAAAP8AAAD/BQUF/wAAAP9lZWX///////39/f//////x8fH/w4ODv8AAAD/aGho//////+Dg4P/AAAA/wQEBP8AAAD/AAAA/wAAAP8AAAD/AgIC/wAAAP9OTk7/xMTE//X19f//////+vr6/9bW1v9tbW3/BAQE/wEBAf8DAwP/AgIC/wICAv8CAgL/BAQE/wAAAP+8vLz///////z8/P/5+fn/Nzc3/wAAAP8fHx//1tbW/xoaGv8AAAD/AQEB/wAAAP8AAAD/AAAA/wEBAf8AAAD/lZWV///////+/v7///////7+/v///////f39//////+3t7f/CAgI/wAAAP8BAQH/AAAA/wAAAP8CAgL/AAAA/zAwMP/9/f3///////////+Dg4P/AAAA/wYGBv8sLCz/BAQE/wAAAP8AAAD/AAAA/wAAAP8DAwP/AAAA/3BwcP//////+vr6//z8/P/+/v7///////7+/v/9/f3/+vr6//////+lpaX/Ghoa/yUlJf8lJSX/JSUl/yQkJP8lJSX/HR0d/8/Pz////////////9TU1P8DAwP/AgIC/wICAv8BAQH/AAAA/wAAAP8AAAD/AQEB/wAAAP8YGBj/6urq///////6+vr//Pz8//z8/P/8/Pz//Pz8//z8/P/8/Pz/+vr6//39/f/19fX/9vb2//j4+P/39/f/9/f3//b29v/19fX/9/f3///////9/f3//////0dHR/8AAAD/BAQE/wAAAP8AAAD/AAAA/wAAAP8DAwP/AAAA/1NTU////////Pz8//////////////////////////////////////////////////////////////////////////////////////////////////z8/P//////v7+//wAAAP8CAgL/AAAA/wAAAP8AAAD/AAAA/wMDA/8AAAD/XFxc/8fHx/++vr7/vr6+/729vf+8vLz/vLy8/8DAwP+9vb3/t7e3/7e3t/+9vb3/v7+//76+vv+4uLj/tbW1/729vf/AwMD/urq6/7a2tv/v7+////////39/f//////SUlJ/wAAAP8DAwP/AAAA/wAAAP8AAAD/AAAA/wEBAf8BAQH/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/8XFxf///////f39///////MzMz/BQUF/wAAAP8BAQH/AAAA/wAAAP8AAAD/AAAA/wICAv8FBQX/BAQE/wQEBP8EBAT/BAQE/wUFBf8EBAT/BAQE/wQEBP8EBAT/BQUF/wQEBP8CAgL/AgIC/wICAv8CAgL/AgIC/wICAv8AAAD/xcXF/////////////f39//////9xcXH/AAAA/wQEBP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP/FxcX/////////////////+/v7//T09P8wMDD/AAAA/wMDA/8AAAD/AQEB/wAAAP8aGhr/Ojo6/zc3N/83Nzf/Nzc3/zg4OP84ODj/Nzc3/zg4OP83Nzf/NjY2/zk5Of8sLCz/AAAA/wAAAP8AAAD/AAAA/wEBAf8AAAD/EBAQ/+Dg4P///////v7+///////e3t7/0tLS/9DQ0P8GBgb/AAAA/wEBAf8DAwP/AAAA/1BQUP///////Pz8///////////////////////////////////////7+/v//////5qamv8AAAD/AwMD/wAAAP8AAAD/AgIC/wAAAP8wMDD//v7+//////////////////z8/P9FRUX/29vb/6enp/8AAAD/AwMD/wICAv8AAAD/FhYW/+jo6P///////Pz8//7+/v/+/v7//v7+//7+/v/+/v7//f39//v7+///////Nzc3/wAAAP8CAgL/AAAA/wAAAP8DAwP/AAAA/2BgYP/////////////////8/Pz//////319ff8bGxv/+fn5/319ff8AAAD/BQUF/wMDA/8AAAD/bm5u///////6+vr//Pz8//7+/v/+/v7//v7+//z8/P/5+fn//////6Ghof8AAAD/AgIC/wAAAP8AAAD/AAAA/wICAv8AAAD/v7+///////////////////7+/v//////5+fn/w0NDf8kJCT/3Nzc/11dXf8AAAD/AwMD/wEBAf8AAAD/jIyM///////+/v7///////7+/v///////f39//////+2trb/CAgI/wAAAP8BAQH/AAAA/wAAAP8CAgL/AAAA/zMzM/////////////////////////////z8/P//////fn5+/wAAAP8VFRX/s7Oz/1JSUv8AAAD/AgIC/wICAv8AAAD/SEhI/8PDw//y8vL///////n5+f/Q0ND/ZmZm/wQEBP8BAQH/AQEB/wAAAP8AAAD/AAAA/wQEBP8AAAD/Ozs7/////////////////////////////v7+///////39/f/NDQ0/wAAAP8KCgr/aGho/yoqKv8AAAD/AQEB/wICAv8AAAD/AAAA/xoaGv82Njb/JiYm/wMDA/8AAAD/AgIC/wEBAf8AAAD/AAAA/wAAAP8FBQX/AAAA/2tra/9gYGD/vLy8/////////////////////////////f39///////V1dX/ExMT/wAAAP8EBAT/EhIS/wEBAf8AAAD/AAAA/wMDA/8CAgL/AAAA/wAAAP8AAAD/AQEB/wMDA/8BAQH/AAAA/wAAAP8AAAD/BAQE/wAAAP8wMDD//////6enp/+CgoL//////////////////////////////////Pz8///////ExMT/EBAQ/wAAAP8CAgL/AgIC/wAAAP8AAAD/AAAA/wAAAP8BAQH/AwMD/wICAv8AAAD/AAAA/wAAAP8AAAD/AgIC/wQEBP8AAAD/MDAw/+Hh4f//////ycnJ/0dHR////////////////////////////////////////Pz8///////Y2Nj/MjIy/wAAAP8BAQH/AwMD/wMDA/8BAQH/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/AAAA/1FRUf/y8vL////////////V1dX/QkJC/////////////////////////////////////////////f39///////5+fn/hISE/xMTE/8AAAD/AQEB/wAAAP8BAQH/AgIC/wICAv8DAwP/AgIC/wAAAP8AAAD/BAQE/y4uLv+np6f///////z8/P/4+Pj//////62trf8uLi7//////////////////////////////////////////////////f39//39/f//////7+/v/5qamv88PDz/ERER/wAAAP8AAAD/AAAA/wAAAP8AAAD/AwMD/wEBAf8VFRX/tbW1/////////////v7+///////r6+v/Hh4e/2NjY////////////////////////////////////////////////////////v7+//z8/P/////////////////n5+f/xMTE/7y8vP++vr7/dHR0/xYWFv8AAAD/AQEB/wAAAP8AAAD/ICAg/0RERP9gYGD/TExM/wgICP8TExP/4eHh//////////////////////////////////////////////////////////////////7+/v/7+/v//v7+//////////////////7+/v//////7+/v/7u7u/9nZ2f/MzMz/w8PD/8AAAD/AQEB/wAAAP8AAAD/QEBA/9bW1v///////f39/////////////////////////////////////////////////////////////////////////////f39//z8/P/8/Pz//Pz8//z8/P//////////////////////3t7e/8TExP/CwsL/wcHB/9XV1f///////v7+//7+/v//////AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA="></td>
<td style="text-align:center" width="30pix"><img src="data:image/ico;base64,AAABAAEAICAAAAEAIACoEAAAFgAAACgAAAAgAAAAQAAAAAEAIAAAAAAAABAAABILAAASCwAAAAAAAAAAAAD///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////39/f/39/f/9vb2//b29v/29vb/9vb2//v7+///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////+/v7/9nZ2f+tra3/aWlp/0BAQP8/Pz//Pz8//z8/P/8+Pj7/XFxc/5ycnP/CwsL/6+vr/////////////////////////////////////////////////////////////////////////////////////////////Pz8/8HBwf9hYWH/HR0d/wUFBf8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AgIC/wsLC/8zMzP/hISE/9nZ2f///////////////////////////////////////////////////////////////////////////+Tk5P9vb2//FRUV/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/JSUl/5KSkv/19fX////////////////////////////////////////////////////////////Ly8v/QEBA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/BwcH/2dnZ//m5ub/////////////////////////////////////////////////0tLS/zAwMP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/05OTv/l5eX//////////////////////////////////////+fn5/9DQ0P/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/2tra//4+Pj////////////////////////////9/f3/fX19/wEBAf8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8EBAT/AQEB/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/CQkJ/5ubm////////////////////////////9TU1P8cHBz/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AQEB/x0dHf9bW1v/hISE/6urq/+Xl5f/Y2Nj/x4eHv8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/Ly8v/+Hh4f//////////////////////fn5+/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/xUVFf9wcHD/2NjY//z8/P/////////////////9/f3/0NDQ/0lJSf8CAgL/AgIC/wAAAP8AAAD/AAAA/wAAAP8CAgL/kJCQ/////////////////+rq6v8xMTH/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8JCQn/dnZ2/8DAwP/b29v/8vLy////////////////////////////6Ojo/09PT/9ISEj/Hh4e/wAAAP8AAAD/AAAA/wAAAP80NDT/6+vr////////////xMTE/wsLC/8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wICAv8KCgr/CgoK/xgYGP9ISEj/wMDA//z8/P//////////////////////1tbW/56env94eHj/AAAA/wAAAP8AAAD/AAAA/wkJCf+6urr///////////+mpqb/AwMD/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8XFxf/enp6/8DAwP/z8/P/////////////////7e3t/7e3t/8ICAj/AAAA/wAAAP8AAAD/AAAA/3R0dP//////7+/v/3Nzc/8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8JCQn/MzMz/05OTv8qKir/BwcH/wAAAP8AAAD/NDQ0/9/f3///////////////////////09PT/xUVFf8AAAD/AAAA/wAAAP8AAAD/Pj4+//Pz8/+Wlpb/SEhI/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/Ghoa/5eXl//u7u7/+vr6/+fn5/+np6f/aWlp/3h4eP/T09P//v7+///////////////////////m5ub/Jycn/wAAAP8AAAD/AAAA/wAAAP8fHx//1tbW/4qKiv8GBgb/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/xEREf+xsbH///////////////////////////////////////////////////////////////////////Ly8v9JSUn/Dw8P/wAAAP8AAAD/AAAA/wsLC/+5ubn/srKy/wkJCf8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/HBwc/93d3f//////////////////////////////////////////////////////////////////////5ubm/6Ghof9eXl7/AAAA/wAAAP8AAAD/CQkJ/7Kysv+7u7v/GRkZ/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8FBQX/a2tr/5aWlv+np6f////////////////////////////////////////////////////////////8/Pz/+/v7/29vb/8AAAD/AAAA/wAAAP8CAgL/jo6O/319ff8eHh7/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/AQEB/4iIiP//////////////////////////////////////////////////////////////////////kZGR/wAAAP8AAAD/AAAA/xEREf+hoaH/lZWV/wUFBf8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/iIiI//7+/v////////////////////////////////////////////////////////////////+RkZH/AAAA/wAAAP8AAAD/ODg4/9/f3//Q0ND/Gxsb/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8UFBT/gYGB/+np6f///////////////////////////////////////////////////////////3Nzc/8MDAz/AAAA/wAAAP9LS0v/+Pj4//j4+P9aWlr/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8CAgL/QkJC/9/f3//////////////////////////////////////////////////+/v7/xsbG/01NTf8AAAD/AAAA/4ODg////////////8LCwv8UFBT/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8FBQX/Ly8v/z8/P/8+Pj7/tra2///////////////////////////////////////////////////////Jycn/Ghoa/wAAAP8EBAT/r6+v////////////9PT0/z09Pf8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AQEB/2NjY//p6en/9/f3//b29v/7+/v/////////////////////////////////////////////////8PDw/1dXV/8AAAD/AQEB/xgYGP/Q0ND////////////29vb/Pz8//wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8SEhL/ycnJ/////////////////////////////////////////////////////////////////+7u7v9wcHD/BAQE/wAAAP8wMDD/e3t7//f39/////////////n5+f9JSUn/AAAA/w4ODv9YWFj/SkpK/z4+Pv9XV1f/MzMz/wAAAP91dXX//v7+//////////////////////////////////////////////////39/f/Jycn/VlZW/wMDA/8AAAD/GRkZ/5mZmf/Ozs7//////////////////////4yMjP8BAQH/gICA//z8/P/5+fn/9vb2//z8/P/e3t7/bm5u/zo6Ov+0tLT///////////////////////////////////////39/f/ExMT/ampq/xsbG/8AAAD/AAAA/xEREf+Xl5f/+fn5//v7+///////////////////////1dXV/1ZWVv/l5eX////////////////////////////8/Pz/39/f/8LCwv/4+Pj//////////////////////////////////f39/9nZ2f+VlZX/NDQ0/w0NDf8/Pz//r6+v//z8/P/////////////////////////////////7+/v/5+fn//7+/v////////////////////////////////////////////////////////////////////////////v7+//c3Nz/tbW1/319ff+Tk5P/x8fH/+7u7v///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////Pz8/+zs7P/w8PD/9vb2////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA="></td>
<td style="text-align:center" width="30pix"><img src="data:image/ico;base64,AAABAAEAICAAAAEAIACoEAAAFgAAACgAAAAgAAAAQAAAAAEAIAAAAAAAABAAAHQSAAB0EgAAAAAAAAAAAAD///////////////////////////////////////////////////////////39/f/7+/v//f39///////////////////////////////////////////////////////7+/v/+/v7//7+/v/////////////////////////////////////////////////////////////////////////////////7+/v//v7+///////9/f3/2tra/66urv+EhIT/ZmZm/2dnZ/90dHT/mpqa/6urq//a2tr/9/f3/////////////v7+//39/f/////////////////////////////////////////////////////////////////+/v7//Pz8///////d3d3/enp6/zY2Nv8FBQX/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wQEBP8hISH/WFhY/5+fn//o6Oj///////7+/v///////////////////////////////////////////////////////v7+//39/f/9/f3/lJSU/xMTE/8AAAD/AQEB/wEBAf8DAwP/BAQE/wQEBP8EBAT/BAQE/wQEBP8DAwP/AQEB/wAAAP8BAQH/AAAA/xISEv/FxcX///////z8/P////////////////////////////////////////////7+/v//////9vb2/19fX/8AAAD/AgIC/wQEBP8DAwP/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/AgIC/wQEBP8HBwf/AAAA/5mZmf//////+/v7/////////////////////////////////////////////v7+//////9XV1f/AAAA/wYGBv8BAQH/AAAA/wAAAP8AAAD/AgIC/wQEBP8EBAT/BAQE/wQEBP8EBAT/BAQE/wQEBP8CAgL/AAAA/wQEBP8AAAD/m5ub///////7+/v///////////////////////////////////////z8/P//////ioqK/wAAAP8FBQX/AAAA/wAAAP8AAAD/AwMD/wICAv8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8CAgL/CAgI/wAAAP+ZmZn///////v7+//////////////////////////////////9/f3//////9bW1v8ICAj/AAAA/wEBAf8AAAD/AAAA/wMDA/8AAAD/AQEB/yUlJf9iYmL/l5eX/5mZmf+YmJj/nJyc/319ff9SUlL/Hh4e/wICAv8EBAT/AAAA/5ubm///////+/v7//////////////////////////////////z8/P//////ampq/wAAAP8EBAT/AAAA/wAAAP8CAgL/AAAA/zg4OP+/v7///Pz8///////////////////////////////////////39/f/ycnJ/2FhYf8AAAD/mJiY///////7+/v////////////////////////////+/v7///////X19f8fHx//AAAA/wICAv8AAAD/AgIC/wAAAP9SUlL/+vr6///////+/v7/+/v7//v7+//7+/v/+/v7//v7+//7+/v//Pz8///////+/v7//////9bW1v/Jycn///////39/f////////////////////////////z8/P//////x8fH/wAAAP8BAQH/AAAA/wMDA/8AAAD/Q0ND///////9/f3/+/v7//7+/v///////////////////////////////////////v7+//z8/P/8/Pz/////////////////////////////////////////////////+/v7//////+dnZ3/AAAA/wQEBP8AAAD/AwMD/wAAAP+pqan///////n5+f/+/v7//v7+//7+/v/+/v7//v7+//7+/v/+/v7//v7+//7+/v/+/v7//v7+//7+/v/8/Pz//Pz8//7+/v/+/v7////////////////////////////7+/v//////5mZmf8AAAD/BAQE/wEBAf8AAAD/CQkJ/+Dg4P///////f39//////////////////////////////////////////////////////////////////////////////////////////////////////////////////v7+///////mZmZ/wAAAP8EBAT/AAAA/wAAAP8GBgb/NTU1/zc3N/82Njb/Nzc3/zc3N/83Nzf/Nzc3/zc3N/83Nzf/Nzc3/zc3N/83Nzf/Nzc3/zc3N/83Nzf/Nzc3/zc3N/8zMzP/Q0ND//Ly8v///////////////////////Pz8//////++vr7/AAAA/wICAv8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AQEB/wAAAP8QEBD/7u7u//////////////////7+/v/+/v7//////+jo6P8QEBD/AAAA/wEBAf8AAAD/AAAA/wICAv8DAwP/AwMD/wMDA/8DAwP/AwMD/wMDA/8DAwP/AwMD/wMDA/8DAwP/AwMD/wMDA/8DAwP/AwMD/wMDA/8EBAT/AAAA/xISEv/v7+///////////////////v7+//39/f/9/f3//////0dHR/8AAAD/AwMD/wAAAP8AAAD/BAQE/wQEBP8EBAT/BAQE/wQEBP8EBAT/BAQE/wQEBP8EBAT/BAQE/wICAv8AAAD/AAAA/wAAAP8AAAD/AAAA/wEBAf8AAAD/EBAQ/+/v7/////////////j4+P/R0dH///////n5+f//////srKy/wAAAP8DAwP/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AQEB/wAAAP8RERH/7+/v///////+/v7//////2dnZ//Ozs7///////r6+v//////T09P/wAAAP8CAgL/DAwM/5CQkP+bm5v/mJiY/5mZmf+ZmZn/mZmZ/5mZmf+ZmZn/lpaW/6SkpP9bW1v/AAAA/wICAv8AAAD/AAAA/wAAAP8CAgL/AAAA/ycnJ//8/Pz///////v7+///////c3Nz/xcXF//f39////////7+/v/n5+f/Kysr/wAAAP8ODg7/4uLi///////9/f3////////////////////////////7+/v//////5mZmf8AAAD/BAQE/wAAAP8AAAD/AAAA/wMDA/8AAAD/SUlJ///////8/Pz//f39///////Pz8//AAAA/xcXF//Kysr////////////W1tb/Hx8f/wAAAP+MjIz///////f39//7+/v/+/v7//v7+//7+/v/+/v7//f39///////bGxs/wAAAP8EBAT/AAAA/wAAAP8AAAD/BAQE/wAAAP+Hh4f///////v7+////////v7+//////9DQ0P/AAAA/wwMDP+SkpL////////////r6+v/RUVF/xISEv/r6+v///////7+/v/////////////////9/f3//v7+//X19f8lJSX/AAAA/wICAv8AAAD/AAAA/wAAAP8AAAD/AwMD/9PT0////////f39///////8/Pz//////6Ojo/8AAAD/BgYG/wAAAP8+Pj7/xsbG////////////pKSk/5eXl///////+fn5//v7+//7+/v//Pz8//z8/P//////goKC/wAAAP8DAwP/AAAA/wAAAP8AAAD/AwMD/wAAAP9FRUX///////7+/v///////////////////////////0lJSf8AAAD/BwcH/wAAAP8ICAj/S0tL/4yMjP/4+Pj/9vb2//7+/v//////////////////////8vLy/3Nzc/8BAQH/AQEB/wAAAP8AAAD/AAAA/wAAAP8CAgL/AQEB/8LCwv///////f39//////////////////39/f//////29vb/xQUFP8AAAD/BgYG/wICAv8AAAD/AgIC/wwMDP8jIyP/dXV1/5+fn/+Wlpb/oKCg/2BgYP8SEhL/AQEB/wICAv8AAAD/AAAA/wAAAP8AAAD/BQUF/wAAAP96enr///////z8/P////////////////////////////z8/P//////u7u7/wYGBv8AAAD/BAQE/wMDA/8EBAT/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8DAwP/AAAA/wAAAP8AAAD/AQEB/wYGBv8AAAD/R0dH//39/f/+/v7///////////////////////////////////////z8/P//////sbGx/xUVFf8AAAD/BAQE/wMDA/8BAQH/AgIC/wQEBP8EBAT/BAQE/wQEBP8DAwP/AQEB/wAAAP8AAAD/AQEB/wQEBP8DAwP/AAAA/09PT//19fX///////7+/v////////////////////////////////////////////v7+///////4uLi/0pKSv8AAAD/AQEB/wICAv8EBAT/BAQE/wICAv8BAQH/AQEB/wEBAf8DAwP/BAQE/wMDA/8BAQH/AAAA/woKCv97e3v/+fn5//7+/v/+/v7///////////////////////////////////////////////////////v7+///////+Pj4/6Ojo/8uLi7/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/AAAA/w0NDf9cXFz/zs7O///////8/Pz//v7+//////////////////////////////////////////////////////////////////39/f/8/Pz///////v7+//IyMj/dnZ2/2hoaP8zMzP/CgoK/xISEv8NDQ3/VFRU/2dnZ/+UlJT/5ubm///////+/v7/+/v7//7+/v/////////////////////////////////////////////////////////////////////////////////7+/v//v7+//////////////////X19f/t7e3/7+/v/+7u7v/7+/v//////////////////Pz8//z8/P///////////////////////////////////////////////////////////////////////////////////////////////////////Pz8//v7+//6+vr//f39//////////////////z8/P/6+vr/+/v7//39/f//////////////////////////////////////////////////////AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA="></td>
<td style="text-align:center" width="30pix"><img src="data:image/ico;base64,AAABAAEAICAAAAEAIACoEAAAFgAAACgAAAAgAAAAQAAAAAEAIAAAAAAAABAAAHQSAAB0EgAAAAAAAAAAAAD//////////////////////////////////////////////////////////////////////Pz8//X19f/19fX/9fX1//X19f/8/Pz////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////z8/P/ysrK/5iYmP9bW1v/PT09/z4+Pv8+Pj7/PT09/1tbW/+YmJj/ysrK//Pz8//////////////////////////////////////////////////////////////////////////////////////////////////w8PD/pqam/0FBQf8cHBz/Li4u/0dHR/9sbGz/hYWF/4WFhf9sbGz/R0dH/y4uLv8cHBz/QUFB/6ampv/w8PD////////////////////////////////////////////////////////////////////////////9/f3/vb29/0NDQ/8eHh7/ampq/7q6uv/o6Oj/+fn5///////////////////////5+fn/6Ojo/7q6uv9qamr/Hh4e/0NDQ/+9vb3//f39////////////////////////////////////////////////////////////+Pj4/46Ojv8aGhr/UVFR/8bGxv/9/f3///////////////////////////////////////////////////////39/f/Gxsb/UVFR/xoaGv+Ojo7/+Pj4//////////////////////////////////////////////////j4+P+BgYH/FhYW/4ODg//x8fH////////////////////////////////////////////////////////////////////////////x8fH/g4OD/xYWFv+BgYH/+Pj4///////////////////////////////////////+/v7/j4+P/xcXF/+Wlpb/+/v7///////////////////////////////////////////////////////////////////////////////////////7+/v/lpaW/xcXF/+Pj4///v7+/////////////////////////////////7y8vP8bGxv/g4OD//v7+////////f39//7+/v/////////////////////////////////////////////////////////////////////////////////7+/v/g4OD/xsbG/+8vLz////////////////////////////v7+//RUVF/1NTU//x8fH///////7+/v+YmJj/goKC/+Pj4//////////////////////////////////////////////////////////////////////////////////x8fH/U1NT/0VFRf/v7+///////////////////////6ampv8hISH/xcXF/////////////////39/f/8BAQH/Ly8v/5WVlf/o6Oj////////////////////////////////////////////////////////////////////////////FxcX/ISEh/6ampv/////////////////09PT/QkJC/2tra//+/v7/////////////////4ODg/y0tLf8UFBT/HBwc/zU1Nf+lpaX/8PDw//////////////////////////////////////////////////////////////////7+/v9ra2v/QkJC//T09P///////////8rKyv8cHBz/ubm5////////////////////////////kZGR/yAgIP+fn5//Xl5e/xkZGf9GRkb/t7e3//j4+P///////////////////////////////////////////////////////////7m5uf8cHBz/ysrK////////////mJiY/y4uLv/o6Oj////////////////////////////m5ub/NTU1/2ZmZv/x8fH/u7u7/01NTf8YGBj/X19f/8vLy//7+/v/////////////////////////////////////////////////6Ojo/y4uLv+YmJj///////39/f9bW1v/R0dH//n5+f////////////////////////////////+ioqL/Gxsb/76+vv/8/Pz/7+/v/6mpqf86Ojr/FxcX/4+Pj//8/Pz////////////////////////////////////////////5+fn/R0dH/1tbW//9/f3/9fX1/z4+Pv9sbGz//////////////////////////////////////+/v7/9ERET/UVFR//Dw8P/4+Pj/+Pj4/4ODg/8DAwP/GBgY/8zMzP////////////////////////////////////////////////9sbGz/Pj4+//X19f/19fX/Pj4+/4WFhf///////////////////////////////////////////7Ozs/8ZGRn/rKys//j4+P+SkpL/Dg4O/wAAAP8AAAD/ZWVl//n5+f///////////////////////////////////////////4WFhf8+Pj7/9fX1//X19f8+Pj7/hYWF////////////////////////////////////////////9/f3/1xcXP88PDz/g4OD/w8PD/8AAAD/AAAA/wAAAP8PDw//ubm5////////////////////////////////////////////hYWF/z4+Pv/19fX/9fX1/z4+Pv9sbGz/////////////////////////////////////////////////x8fH/xkZGf8EBAT/AAAA/wAAAP8AAAD/AAAA/wAAAP9MTEz/8fHx//////////////////////////////////////9sbGz/Pj4+//X19f/9/f3/W1tb/0dHR//5+fn////////////////////////////////////////////7+/v/ioqK/xQUFP8AAAD/AAAA/wAAAP8AAAD/AAAA/wgICP+oqKj/////////////////////////////////+fn5/0dHR/9bW1v//f39//////+YmJj/Li4u/+jo6P/////////////////////////////////////////////////6+vr/ycnJ/2BgYP8ODg7/AAAA/wAAAP8AAAD/AAAA/zs7O//p6en////////////////////////////o6Oj/Li4u/5iYmP///////////8rKyv8cHBz/ubm5////////////////////////////////////////////////////////////9/f3/7e3t/9ISEj/BwcH/wAAAP8AAAD/BAQE/5mZmf///////////////////////////7m5uf8cHBz/ysrK////////////9PT0/0JCQv9ra2v//v7+//////////////////////////////////////////////////////////////////Dw8P+mpqb/OTk5/wQEBP8AAAD/NDQ0/+Tk5P/////////////////+/v7/a2tr/0JCQv/09PT/////////////////pqam/yEhIf/FxcX////////////////////////////////////////////////////////////////////////////o6Oj/mJiY/zIyMv8CAgL/hoaG/////////////////8XFxf8hISH/pqam///////////////////////v7+//RUVF/1NTU//x8fH/////////////////////////////////////////////////////////////////////////////////5OTk/4WFhf+dnZ3////////////x8fH/U1NT/0VFRf/v7+////////////////////////////+8vLz/Gxsb/4ODg//7+/v//////////////////////////////////////////////////////////////////////////////////v7+//7+/v//////+/v7/4ODg/8bGxv/vLy8//////////////////////////////////7+/v+Pj4//FxcX/5aWlv/7+/v///////////////////////////////////////////////////////////////////////////////////////v7+/+Wlpb/FxcX/4+Pj//+/v7///////////////////////////////////////j4+P+BgYH/FhYW/4ODg//x8fH////////////////////////////////////////////////////////////////////////////x8fH/g4OD/xYWFv+BgYH/+Pj4//////////////////////////////////////////////////j4+P+Ojo7/Ghoa/1FRUf/Gxsb//f39///////////////////////////////////////////////////////9/f3/xsbG/1FRUf8aGhr/jo6O//j4+P////////////////////////////////////////////////////////////39/f+9vb3/Q0ND/x4eHv9qamr/urq6/+jo6P/5+fn///////////////////////n5+f/o6Oj/urq6/2pqav8eHh7/Q0ND/729vf/9/f3////////////////////////////////////////////////////////////////////////////w8PD/pqam/0FBQf8cHBz/Li4u/0dHR/9sbGz/hYWF/4WFhf9sbGz/R0dH/y4uLv8cHBz/QUFB/6ampv/w8PD/////////////////////////////////////////////////////////////////////////////////////////////////8/Pz/8rKyv+YmJj/W1tb/z09Pf8+Pj7/Pj4+/z09Pf9bW1v/mJiY/8rKyv/z8/P////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////8/Pz/9fX1//X19f/19fX/9fX1//z8/P//////////////////////////////////////////////////////////////////////AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA="></td>
<td style="text-align:center" width="30pix"><img src="data:image/ico;base64,AAABAAEAICAAAAEAIACoEAAAFgAAACgAAAAgAAAAQAAAAAEAIAAAAAAAABAAAHQSAAB0EgAAAAAAAAAAAAD////////////////////////////////+/v7/+/v7//v7+//6+vr//f39/////////////////////////////v7+//v7+//7+/v/+/v7//v7+//7+/v/+/v7//v7+//8/Pz//////////////////////////////////////////////////////////////////Pz8//7+/v/////////////////29vb/2tra//Pz8//9/f3/+/v7//7+/v///////////////////////////////////////////////////////////////////////////////////////////////////////v7+//z8/P//////6urq/6SkpP+EhIT/XV1d/0JCQv9+fn7/+fn5///////9/f3//////7Gxsf9hYWH/Z2dn/2VlZf9lZWX/aGho/2tra/9fX1//bm5u/+3t7f///////v7+////////////////////////////////////////////+vr6/8XFxf8pKSn/AAAA/wAAAP8TExP/s7Oz/8nJyf+cnJz/mpqa/7CwsP/z8/P//////21tbf8AAAD/AwMD/wAAAP8AAAD/AQEB/wAAAP+hoaH///////39/f///////////////////////////////////////f39//////97e3v/AAAA/wMDA/8AAAD/gICA//////9hYWH/AAAA/wICAv8BAQH/AAAA/zAwMP/e3t7/+Pj4/zc3N/8AAAD/AAAA/3Z2dv+fn5//0dHR///////+/v7///////////////////////////////////////z8/P//////gYGB/wAAAP8ICAj/AAAA/2VlZf//////VVVV/wAAAP89PT3/mpqa/5mZmf9KSkr/AAAA/yoqKv//////s7Oz/wAAAP8AAAD/lJSU///////7+/v//v7+///////////////////////////////////////9/f3//////+Dg4P8SEhL/AAAA/wMDA/8AAAD/1tbW/8fHx/8AAAD/ExMT/+jo6P///////////+vr6/8ZGRn/AAAA/6Wlpf/09PT/DQ0N/wAAAP9lZWX///////n5+f////////////////////////////////////////////v7+///////dHR0/wAAAP8GBgb/AAAA/yYmJv//////nZ2d/wAAAP8WFhb/7Ozs//v7+//19fX//////zs7O/8AAAD/oaGh//7+/v8RERH/AAAA/2dnZ///////+/v7/////////////////////////////////////////////////+jo6P8SEhL/AAAA/wUFBf8AAAD/gICA///////Gxsb/AAAA/w0NDf/Z2dn////////////o6Oj/GBgY/wAAAP+ysrL/7Ozs/wgICP8AAAD/j4+P///////4+Pj/+/v7//z8/P/8/Pz//v7+////////////////////////////xMTE/wAAAP8CAgL/BAQE/wAAAP+YmJj///////////9fX1//AAAA/yQkJP+enp7/jIyM/yYmJv8AAAD/NDQ0//////+bm5v/AAAA/wAAAP/Hx8f///////z8/P//////////////////////+/v7//v7+//9/f3///////////9paWn/AAAA/wQEBP8DAwP/AAAA/3Fxcf///////v7+//X19f9jY2P/AgIC/wAAAP8BAQH/AAAA/0JCQv/y8vL/5ubm/ykpKf8AAAD/ZmZm///////6+vr/q6ur/5GRkf9xcXH/ra2t/+rq6v///////////////////////////6Ghof8AAAD/AgIC/wICAv8AAAD/Hh4e/+3t7f//////+/v7///////ExMT/fn5+/4KCgv+1tbX//////+bm5v8vLy//AAAA/xYWFv/m5ub//////8XFxf8AAAD/AQEB/wEBAf8AAAD/ExMT/2BgYP9ubm7/rq6u////////////zMzM/wAAAP8BAQH/AAAA/wICAv8AAAD/r6+v///////c3Nz/zc3N//T09P////////////j4+P97e3v/HR0d/wAAAP8xMTH/1dXV//////+srKz/EhIS/wUFBf8FBQX/AAAA/wAAAP8BAQH/BwcH/2JiYv/g4OD////////////39/f/MTEx/wAAAP8CAgL/AQEB/wAAAP8VFRX/4uLi///////CwsL/SUlJ/ykpKf8eHh7/AAAA/wAAAP8RERH/kJCQ//b29v/9/f3/ioqK/w4ODv8AAAD/AAAA/xAQEP+dnZ3/29vb/+Li4v//////////////////////+/v7//////+fn5//AAAA/wMDA/8AAAD/AQEB/wAAAP88PDz/0tLS///////U1NT/tbW1/3V1df9lZWX/v7+//+fn5///////3Nzc/2tra/8AAAD/AAAA/wkJCf9mZmb/5OTk//j4+P+tra3/oqKi/52dnf+Ojo7/0tLS/////////////v7+//////8yMjL/AAAA/wMDA/8AAAD/AgIC/wICAv8AAAD/cHBw////////////9vb2/+zs7P/n5+f/nZ2d/yUlJf8AAAD/AgIC/wMDA/+BgYH/+vr6///////IyMj/MDAw/wAAAP8CAgL/BAQE/wAAAP9sbGz////////////9/f3//////6+vr/8DAwP/AwMD/wEBAf8AAAD/AwMD/wEBAf8BAQH/QUFB/5mZmf/d3d3/lpaW/2hoaP8DAwP/Nzc3/5CQkP+xsbH/6enp/+3t7f+Wlpb/Pz8//wICAv8AAAD/BAQE/wQEBP8ICAj/AAAA/2tra//////////////////7+/v//////3h4eP8AAAD/BQUF/wAAAP8AAAD/AAAA/wMDA/8CAgL/AAAA/1hYWP/u7u7//v7+//Ly8v/u7u7/w8PD/319ff9UVFT/ExMT/wAAAP8AAAD/AwMD/wICAv8AAAD/AAAA/wQEBP8AAAD/hoaG///////////////////////+/v7/+/v7/4KCgv8AAAD/AQEB/wAAAP8AAAD/AAAA/wMDA/8FBQX/AAAA/xEREf/Kysr//////+vr6/9gYGD/AAAA/wEBAf8BAQH/BwcH/wQEBP8AAAD/AAAA/wAAAP8BAQH/AwMD/wEBAf/Dw8P////////////////////////////8/Pz//////5KSkv8AAAD/AgIC/wAAAP8AAAD/AAAA/wAAAP8EBAT/AAAA/x4eHv/s7Oz///////39/f/x8fH/uLi4/zMzM/8AAAD/AgIC/wAAAP8AAAD/AwMD/wUFBf8AAAD/lpaW///////8/Pz///////////////////////7+/v/+/v7/+fn5/ykpKf8AAAD/AgIC/wAAAP8AAAD/AAAA/wAAAP8FBQX/AAAA/42Njf//////+fn5//7+/v//////8PDw/5WVlf8HBwf/AAAA/wEBAf8BAQH/AAAA/2tra////////v7+//////////////////////////////////v7+///////hoaG/wAAAP8EBAT/AAAA/wAAAP8AAAD/AAAA/wICAv8AAAD/KSkp//v7+////////f39//v7+//8/Pz//////zg4OP8AAAD/BgYG/y8vL/+FhYX//f39//7+/v/////////////////+/v7//Pz8/////////////f39///////FxcX/AAAA/wEBAf8AAAD/AAAA/wAAAP8AAAD/AQEB/wAAAP8EBAT/zMzM///////9/f3///////z8/P//////PDw8/wAAAP+tra3///////7+/v/8/Pz//v7+/////////////Pz8//Hx8f///////Pz8//v7+//4+Pj//////46Ojv8AAAD/AwMD/wAAAP8AAAD/AAAA/wAAAP8AAAD/BAQE/wAAAP+ZmZn///////v7+////////Pz8//////+YmJj/HBwc/+bm5v//////+vr6////////////////////////////wMDA/729vf/+/v7//v7+///////Y2Nj/HBwc/wAAAP8CAgL/AAAA/wAAAP8AAAD/AAAA/wAAAP8CAgL/AAAA/6ysrP///////Pz8///////+/v7//////9bW1v/Hx8f///////z8/P/////////////////////////////////39/f/QUFB/zQ0NP9ycnL/X19f/xUVFf8AAAD/AQEB/wAAAP8AAAD/AAAA/wAAAP8AAAD/AgIC/wAAAP8aGhr/8vLy///////+/v7//////////////////f39//39/f/+/v7//////////////////////////////////v7+///////u7u7/ODg4/wAAAP8CAgL/AgIC/wEBAf8AAAD/AAAA/wAAAP8AAAD/AAAA/wEBAf8FBQX/AAAA/4SEhP///////f39///////////////////////+/v7//f39/////////////////////////////////////////////f39///////v7+//XV1d/wAAAP8BAQH/AwMD/wQEBP8DAwP/AQEB/wMDA/8FBQX/AAAA/wYGBv90dHT/9fX1///////+/v7//////////////////////////////////////////////////////////////////////////////////f39//z8/P//////f39//wgICP8GBgb/AAAA/wAAAP8AAAD/AAAA/wICAv8CAgL/h4eH///////5+fn//////////////////////////////////////////////////////////////////////////////////////////////////f39//39/f/7+/v/7+/v/6urq/9xcXH/U1NT/woKCv9BQUH/fn5+/93d3f/+/v7//Pz8//7+/v////////////////////////////////////////////////////////////////////////////////////////////////////////////39/f/////////////////8/Pz/7Ozs//j4+P////////////39/f////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////7+/v/7+/v/+vr6//z8/P///////Pz8//r6+v/9/f3/////////////////////////////////////////////////////////////////////////////////////////////////AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA="></td>
<td style="text-align:center" width="30pix"><img src="data:image/ico;base64,AAABAAEAICAAAAEAIACoEAAAFgAAACgAAAAgAAAAQAAAAAEAIAAAAAAAABAAAHQSAAB0EgAAAAAAAAAAAAD////////////////////////////////////////////////+/v7/+/v7//z8/P/+/v7//////////////////////////////////v7+//z8/P/7+/v//v7+/////////////////////////////////////////////////////////////////////////////////////////////Pz8//7+/v/+/v7//////+rq6v/Gxsb/ysrK/8nJyf/Jycn/ysrK/8bGxv/q6ur///////7+/v/+/v7//Pz8/////////////////////////////////////////////////////////////////////////////f39//z8/P//////7u7u/5+fn/9SUlL/Hh4e/wAAAP8BAQH/AAAA/wAAAP8BAQH/AAAA/x4eHv9ISEj/oKCg/+7u7v///////Pz8//39/f////////////////////////////////////////////////////////////39/f/9/f3//////7S0tP8jIyP/AAAA/wEBAf8AAAD/BAQE/wYGBv8DAwP/BAQE/wYGBv8EBAT/AAAA/wEBAf8AAAD/Jycn/7+/v//9/f3//v7+//39/f/////////////////////////////////////////////////8/Pz//////+Pj4/9LS0v/AAAA/wEBAf8DAwP/BAQE/wQEBP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8EBAT/BAQE/wMDA/8BAQH/AAAA/0xMTP/q6ur///////z8/P///////////////////////////////////////Pz8///////Nzc3/GRkZ/wAAAP8EBAT/AgIC/wAAAP8DAwP/AAAA/zExMf9mZmb/urq6/6Wlpf9jY2P/MjIy/wAAAP8DAwP/AQEB/wICAv8DAwP/AAAA/xwcHP/Nzc3///////z8/P////////////////////////////39/f//////zc3N/xYWFv8AAAD/BAQE/wAAAP8AAAD/AgIC/wAAAP9fX1//+vr6///////+/v7//v7+///////6+vr/X19f/wAAAP8CAgL/AAAA/wAAAP8EBAT/AAAA/xYWFv/U1NT///////39/f/////////////////+/v7///////T09P8oKCj/AAAA/wQEBP8AAAD/AAAA/wICAv8AAAD/fHx8///////8/Pz/+vr6//z8/P/8/Pz/+vr6//z8/P//////kJCQ/wEBAf8BAQH/AAAA/wAAAP8EBAT/AAAA/ysrK//09PT///////7+/v////////////39/f//////ampq/wAAAP8EBAT/AAAA/wAAAP8EBAT/AAAA/3h4eP//////+vr6//7+/v///////////////////////v7+//r6+v//////hYWF/wAAAP8DAwP/AAAA/wAAAP8FBQX/AAAA/3Z2dv///////Pz8///////9/f3//////93d3f8NDQ3/AAAA/wEBAf8AAAD/AQEB/wAAAP8SEhL/4eHh///////9/f3//////////////////////////////////v7+///////y8vL/ISEh/wAAAP8CAgL/AAAA/wEBAf8AAAD/FxcX/+3t7f///////v7+//v7+///////fn5+/wAAAP8EBAT/AAAA/wAAAP8DAwP/AAAA/3R0dP//////+/v7////////////////////////////////////////////+/v7//////+enp7/AAAA/wMDA/8AAAD/AAAA/wMDA/8AAAD/d3d3///////8/Pz//////+Li4v8NDQ3/AAAA/wEBAf8AAAD/AQEB/wAAAP8EBAT/1NTU///////9/f3////////////////////////////////////////////+/v7//////+rq6v8VFRX/AAAA/wEBAf8AAAD/AQEB/wAAAP8TExP/6urq////////////w8PD/wAAAP8CAgL/AAAA/wAAAP8CAgL/AAAA/y4uLv/////////////////////////////////////////////////////////////////+/v7//////zc3N/8AAAD/AwMD/wAAAP8AAAD/AQEB/wAAAP/Kysr///////////9wcHD/AAAA/wQEBP8AAAD/AAAA/wMDA/8AAAD/XV1d///////9/f3///////////////////////////////////////////////////////z8/P//////cXFx/wAAAP8DAwP/AAAA/wAAAP8DAwP/AAAA/5CQkP///////////2hoaP8AAAD/BAQE/wAAAP8AAAD/BAQE/wAAAP+ZmZn///////v7+////////////////////////////////////////////////////////Pz8//////+2trb/AAAA/wICAv8AAAD/AAAA/wQEBP8AAAD/aWlp////////////aWlp/wAAAP8EBAT/AAAA/wAAAP8EBAT/AAAA/5iYmP//////+/v7///////////////////////////////////////////////////////8/Pz//////8fHx/8AAAD/AQEB/wAAAP8AAAD/BAQE/wAAAP9qamr///////////9paWn/AAAA/wQEBP8AAAD/AAAA/wQEBP8AAAD/mJiY///////7+/v///////////////////////////////////////////////////////z8/P//////yMjI/wAAAP8BAQH/AAAA/wAAAP8EBAT/AAAA/2lpaf///////////2lpaf8AAAD/BAQE/wAAAP8AAAD/BAQE/wAAAP+ZmZn///////v7+////////////////////////////////////////////////////////Pz8//////+2trb/AAAA/wICAv8AAAD/AAAA/wQEBP8AAAD/aWlp////////////aWlp/wAAAP8EBAT/AAAA/wAAAP8DAwP/AAAA/3Fxcf///////Pz8///////////////////////////////////////////////////////7+/v//////5KSkv8AAAD/BAQE/wAAAP8AAAD/BAQE/wAAAP9wcHD///////////+0tLT/AAAA/wICAv8AAAD/AAAA/wMDA/8AAAD/NjY2///////+/v7///////////////////////////////////////////////////////7+/v//////Pj4+/wAAAP8DAwP/AAAA/wAAAP8CAgL/AAAA/8PDw////////////9jY2P8DAwP/AAAA/wAAAP8AAAD/AQEB/wAAAP8RERH/5OTk///////+/v7////////////////////////////////////////////+/v7///////Dw8P8XFxf/AAAA/wEBAf8AAAD/AQEB/wAAAP8ODg7/6Ojo///////9/f3//////15eXv8AAAD/AwMD/wAAAP8AAAD/AwMD/wAAAP+VlZX///////v7+/////////////////////////////////////////////z8/P//////pKSk/wAAAP8DAwP/AAAA/wAAAP8DAwP/AAAA/29vb////////Pz8//39/f//////zc3N/wYGBv8AAAD/AQEB/wAAAP8CAgL/AAAA/yIiIv/y8vL///////7+/v/////////////////////////////////+/v7//v7+//j4+P8wMDD/AAAA/wICAv8AAAD/AQEB/wAAAP8MDAz/3d3d///////9/f3///////39/f//////VVVV/wAAAP8EBAT/AAAA/wAAAP8DAwP/AAAA/46Ojv//////+fn5//7+/v///////////////////////v7+//n5+f//////kZGR/wAAAP8EBAT/AAAA/wAAAP8EBAT/AAAA/15eXv///////Pz8/////////////v7+///////o6Oj/FhYW/wAAAP8DAwP/AAAA/wAAAP8CAgL/AAAA/5OTk////////Pz8//v7+//7+/v/+/v7//v7+//8/Pz//////7m5uf8LCwv/AAAA/wEBAf8AAAD/AwMD/wAAAP8WFhb/6enp///////+/v7//////////////////Pz8//////+zs7P/CwsL/wEBAf8DAwP/AAAA/wEBAf8BAQH/AgIC/3Fxcf/x8fH///////7+/v/+/v7///////r6+v91dXX/AQEB/wEBAf8BAQH/AAAA/wMDA/8AAAD/Dw8P/8XFxf///////f39/////////////////////////////Pz8///////ExMT/CgoK/wAAAP8EBAT/AQEB/wEBAf8DAwP/AAAA/x0dHf94eHj/p6en/6ampv98fHz/LS0t/wAAAP8DAwP/AQEB/wEBAf8EBAT/AAAA/woKCv/ExMT///////z8/P//////////////////////////////////////+/v7///////ExMT/Jycn/wAAAP8CAgL/BAQE/wMDA/8EBAT/AQEB/wAAAP8AAAD/AAAA/wAAAP8AAAD/BAQE/wMDA/8EBAT/AgIC/wAAAP8sLCz/zMzM///////7+/v//////////////////////////////////////////////////Pz8///////09PT/l5eX/w0NDf8AAAD/AQEB/wEBAf8DAwP/CAgI/wcHB/8HBwf/CAgI/wQEBP8BAQH/AQEB/wAAAP8cHBz/mpqa//b29v///////f39/////////////////////////////////////////////////////////////Pz8//z8/P//////5eXl/29vb/8zMzP/DQ0N/wAAAP8BAQH/AAAA/wAAAP8BAQH/AAAA/w0NDf8yMjL/cHBw/+/v7////////Pz8//39/f///////////////////////////////////////////////////////////////////////v7+//z8/P/////////////////W1tb/w8PD/56env+ampr/m5ub/5qamv+9vb3/19fX/////////////v7+//v7+//+/v7///////////////////////////////////////////////////////////////////////////////////////39/f/7+/v//v7+/////////////////////////////////////////////v7+//v7+//+/v7/////////////////////////////////////////////////AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA="></td>
<td style="text-align:center" width="30pix"><img src="data:image/ico;base64,AAABAAEAICAAAAEAIACoEAAAFgAAACgAAAAgAAAAQAAAAAEAIAAAAAAAABAAAHQSAAB0EgAAAAAAAAAAAAD///////////////////////////////////////////7+/v/9/f3/+/v7//z8/P///////////////////////////////////////////////////////////////////////////////////////Pz8//39/f/////////////////////////////////////////////////9/f3//f39//////////////////Dw8P/Ly8v/ycnJ/8rKyv/Kysr/ysrK/8rKyv/Kysr/ysrK/8rKyv/Kysr/ysrK/8rKyv/Kysr/yMjI/9nZ2f/6+vr///////7+/v///////////////////////////////////////f39///////4+Pj/09PT/5GRkf9DQ0P/FhYW/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/AQEB/1BQUP/i4uL///////7+/v////////////////////////////v7+///////4eHh/zg4OP8AAAD/AQEB/wAAAP8AAAD/AQEB/wEBAf8BAQH/AQEB/wEBAf8BAQH/AQEB/wEBAf8BAQH/AQEB/wEBAf8BAQH/AQEB/wEBAf8DAwP/AAAA/zs7O////////v7+///////////////////////6+vr//////7+/v/8SEhL/AAAA/wICAv8EBAT/AwMD/wEBAf8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wEBAf8EBAT/AAAA/7+/v////////////////////////Pz8//////+/v7//Ghoa/wAAAP8EBAT/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wQEBP8AAAD/m5ub//////////////////39/f//////ra2t/w0NDf8AAAD/AwMD/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AwMD/wAAAP+/v7/////////////9/f3//////87Ozv8FBQX/AQEB/wICAv8AAAD/AAAA/wAAAP8AAAD/AwMD/wMDA/8CAgL/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wMDA/8AAAD/ODg4///////+/v7//v7+////////////V1dX/wAAAP8EBAT/AAAA/wAAAP8AAAD/AAAA/wMDA/8AAAD/AAAA/wAAAP8EBAT/BAQE/wICAv8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/AAAA/yEhIf/Nzc3///////39/f/8/Pz//////6ysrP8AAAD/AwMD/wAAAP8AAAD/AAAA/wAAAP8DAwP/AAAA/0NDQ/+wsLD/Wlpa/wAAAP8CAgL/AQEB/wICAv8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wQEBP8AAAD/gICA///////7+/v///////z8/P//////SUlJ/wAAAP8DAwP/AAAA/wAAAP8AAAD/AgIC/wAAAP9paWn////////////u7u7/cHBw/2pqav84ODj/AAAA/wMDA/8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AgIC/wAAAP8kJCT/8/Pz///////+/v7//////9nZ2f8KCgr/AAAA/wEBAf8AAAD/AAAA/wICAv8AAAD/XFxc///////8/Pz/+/v7//39/f/+/v7///////Dw8P89PT3/AAAA/wUFBf8BAQH/AQEB/wEBAf8AAAD/AAAA/wAAAP8AAAD/AgIC/wAAAP+1tbX///////z8/P//////iYmJ/wAAAP8DAwP/AAAA/wAAAP8DAwP/AAAA/09PT///////+vr6//7+/v///////v7+//v7+//6+vr//Pz8//////9XV1f/AAAA/wMDA/8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8EBAT/AAAA/3Fxcf//////+/v7//b29v8lJSX/AAAA/wICAv8AAAD/AAAA/wQEBP8AAAD/f39////////6+vr////////////////////////////8/Pz//////+bm5v9KSkr/FRUV/xEREf8PDw//AQEB/wAAAP8AAAD/AAAA/wMDA/8AAAD/QEBA///////9/f3/5OTk/xAQEP8AAAD/AQEB/wAAAP8AAAD/AQEB/wAAAP/ExMT///////z8/P/////////////////////////////////+/v7//f39///////v7+//+Pj4/7u7u/8AAAD/AQEB/wAAAP8AAAD/AwMD/wAAAP82Njb///////7+/v/FxcX/AAAA/wAAAP8AAAD/AAAA/wEBAf8AAAD/BAQE/9jY2P///////f39///////////////////////////////////////+/v7//Pz8//7+/v//////7e3t/x4eHv8AAAD/AgIC/wAAAP8CAgL/AAAA/yYmJv/8/Pz//////8XFxf8AAAD/AAAA/wAAAP8AAAD/AQEB/wAAAP8NDQ3/5+fn///////+/v7//////////////////////////////////////////////////v7+//39/f//////NjY2/wAAAP8DAwP/AAAA/wEBAf8AAAD/EBAQ/+7u7v//////x8fH/wAAAP8AAAD/AAAA/wAAAP8AAAD/AQEB/wAAAP/Hx8f///////39/f/////////////////////////////////////////////////9/f3//////9PT0/8GBgb/AAAA/wEBAf8AAAD/AwMD/wAAAP81NTX///////7+/v/q6ur/FxcX/wAAAP8BAQH/AAAA/wAAAP8DAwP/AAAA/6mpqf//////+/v7//////////////////////////////////////////////////z8/P//////oaGh/wAAAP8CAgL/AAAA/wAAAP8DAwP/AAAA/zY2Nv///////v7+//////9fX1//AAAA/wMDA/8AAAD/AAAA/wMDA/8AAAD/QEBA//39/f/9/f3//v7+///////////////////////////////////////+/v7//v7+//j4+P8yMjL/AAAA/wICAv8AAAD/AAAA/wMDA/8AAAD/VlZW///////8/Pz//////7CwsP8AAAD/AwMD/wAAAP8AAAD/AAAA/wICAv8AAAD/m5ub///////4+Pj//v7+/////////////////////////////v7+//j4+P//////oaGh/wAAAP8DAwP/AAAA/wAAAP8AAAD/AwMD/wAAAP+goKD///////v7+///////+Pj4/yYmJv8AAAD/AgIC/wAAAP8AAAD/AAAA/wEBAf8DAwP/paWl///////8/Pz/+/v7//v7+//7+/v/+/v7//v7+//8/Pz//////8jIyP8WFhb/AAAA/wEBAf8AAAD/AAAA/wEBAf8AAAD/BwcH/9jY2P///////f39//z8/P//////hISE/wAAAP8EBAT/AAAA/wAAAP8AAAD/AQEB/wAAAP8NDQ3/gYGB//Ly8v///////v7+///////+/v7//////+3t7f96enr/Dg4O/wAAAP8BAQH/AAAA/wAAAP8AAAD/BAQE/wAAAP9lZWX///////39/f///////f39///////k5OT/ExMT/wAAAP8BAQH/AAAA/wAAAP8AAAD/AQEB/wMDA/8AAAD/ICAg/2VlZf+Ojo7/np6e/4yMjP9paWn/Jycn/wAAAP8DAwP/AQEB/wAAAP8AAAD/AAAA/wEBAf8CAgL/AQEB/8bGxv///////f39/////////////Pz8//////+VlZX/AAAA/wUFBf8BAQH/AAAA/wAAAP8AAAD/AQEB/wQEBP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/BAQE/wEBAf8AAAD/AAAA/wAAAP8BAQH/BQUF/wAAAP+EhIT///////z8/P///////////////////////Pz8//////9eXl7/AAAA/wUFBf8BAQH/AAAA/wAAAP8AAAD/AAAA/wICAv8EBAT/BAQE/wQEBP8EBAT/BAQE/wICAv8AAAD/AAAA/wAAAP8AAAD/AQEB/wQEBP8AAAD/T09P//7+/v/+/v7////////////////////////////+/v7///////Ly8v9dXV3/AAAA/wMDA/8CAgL/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wICAv8DAwP/AAAA/2hoaP///////f39//7+/v///////////////////////////////////////Pz8//////+Pj4//AAAA/wAAAP8EBAT/AwMD/wEBAf8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AQEB/wMDA/8DAwP/AAAA/wMDA/+FhYX///////z8/P/+/v7////////////////////////////////////////////+/v7/+/v7//////+kpKT/ISEh/wAAAP8BAQH/AAAA/wICAv8EBAT/BAQE/wQEBP8EBAT/BAQE/wICAv8BAQH/AAAA/wEBAf8dHR3/k5OT///////7+/v//v7+/////////////////////////////////////////////////////////////Pz8///////19fX/jo6O/zk5Of8LCwv/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/w0NDf8wMDD/lpaW//39/f///////Pz8/////////////////////////////////////////////////////////////////////////////Pz8//7+/v///////////+Hh4f/Dw8P/oaGh/5CQkP9kZGT/fHx8/6Kiov/CwsL/4eHh/////////////v7+//z8/P///////////////////////////////////////////////////////////////////////////////////////v7+//v7+//9/f3//////////////////////////////////////////////////f39//z8/P/+/v7/////////////////////////////////////////////////AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA="></td>
<td style="text-align:center" width="30pix"><img src="data:image/ico;base64,AAABAAEAICAAAAEAIACoEAAAFgAAACgAAAAgAAAAQAAAAAEAIAAAAAAAABAAAHQSAAB0EgAAAAAAAAAAAAD///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////39/f/7+/v/+/v7//v7+//7+/v//f39///////////////////////////////////////+/v7//f39//////////////////////////////////////////////////////////////////////////////////z8/P/9/f3//////////////////////////////////v7+//39/f///////////////////////////////////////f39//7+/v////////////////////////////////////////////////////////////39/f/9/f3////////////i4uL/oKCg/5iYmP+ampr/mpqa/9TU1P///////v7+//39/f////////////7+/v//////1NTU/9ra2v///////Pz8//7+/v/////////////////////////////////////////////////9/f3//v7+//39/f+tra3/RkZG/wkJCf8AAAD/AAAA/wAAAP8AAAD/BgYG/y8vL//Ozs7///////z8/P///////v7+///////6+vr/ZmZm/29vb////////f39//39/f///////////////////////////////////////f39///////i4uL/SEhI/wAAAP8BAQH/AQEB/wQEBP8EBAT/BAQE/wQEBP8CAgL/AAAA/w0NDf+wsLD///////z8/P///////v7+///////7+/v/UVFR/z09Pf/09PT///////39/f////////////////////////////39/f//////1dXV/yAgIP8AAAD/BQUF/wMDA/8BAQH/AAAA/wAAAP8AAAD/AAAA/wAAAP8FBQX/AAAA/yoqKv/6+vr///////7+/v///////f39///////o6Oj/ERER/yAgIP/i4uL///////39/f/////////////////+/v7///////Pz8/8vLy//AAAA/wUFBf8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/BQUF/9jY2P///////f39////////////+vr6//////9zc3P/AAAA/0hISP/+/v7//f39//7+/v////////////39/f//////Y2Nj/wAAAP8FBQX/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wEBAf8AAAD/ycnJ///////8/Pz////////////8/Pz//////76+vv8AAAD/AAAA/3x8fP///////Pz8///////8/Pz//////7a2tv8AAAD/AwMD/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/AQEB/wgICP/g4OD///////39/f////////////7+/v//////5ubm/wwMDP8AAAD/AAAA/6enp////////Pz8///////19fX/KCgo/wAAAP8CAgL/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AgIC/wUFBf8AAAD/WVlZ///////+/v7//////////////////v7+///////5+fn/IiIi/wAAAP8AAAD/KCgo//r6+v///////////7Ozs/8AAAD/AwMD/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/AwMD/wQEBP8BAQH/AAAA/2FhYf/19fX///////7+/v/////////////////+/v7///////39/f8qKir/AAAA/wUFBf8AAAD/tbW1////////////UFBQ/wAAAP8DAwP/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/BAQE/wICAv8AAAD/AAAA/xwcHP+oqKj///////z8/P/+/v7///////////////////////39/f//////3t7e/wcHB/8AAAD/BAQE/wAAAP9iYmL///////v7+/8sLCz/AAAA/wICAv8AAAD/AAAA/wAAAP8AAAD/AQEB/wMDA/8AAAD/BwcH/0JCQv+Kior/9vb2///////8/Pz//v7+/////////////////////////////Pz8//////+ysrL/AAAA/wICAv8DAwP/AAAA/zc3N///////3Nzc/wwMDP8AAAD/AQEB/wAAAP8AAAD/AAAA/wMDA/8BAQH/BgYG/1FRUf/Pz8////////7+/v/+/v7//Pz8///////////////////////////////////////8/Pz//////01NTf8AAAD/AwMD/wAAAP8AAAD/AgIC/8nJyf/FxcX/AAAA/wAAAP8AAAD/AAAA/wAAAP8CAgL/AAAA/wwMDP+np6f///////39/f/8/Pz/+/v7//7+/v//////////////////////////////////////+fn5//////+tra3/AAAA/wICAv8AAAD/AAAA/wAAAP8AAAD/xMTE/8bGxv8AAAD/AAAA/wAAAP8AAAD/AgIC/wAAAP8/Pz//4uLi///////7+/v//Pz8/////////////////////////////////////////////f39//n5+f//////ra2t/wsLC/8AAAD/AQEB/wAAAP8AAAD/AAAA/wAAAP/FxcX/xMTE/wAAAP8AAAD/AAAA/wEBAf8AAAD/Ghoa/+Pj4///////+/v7/////////////////////////////////////////////Pz8//v7+//9/f3//////6CgoP8JCQn/AAAA/wEBAf8AAAD/AAAA/wAAAP8AAAD/AAAA/8TExP/l5eX/ExMT/wAAAP8BAQH/AwMD/wAAAP+VlZX///////r6+v///////////////////////////////////////Pz8//39/f///////////+Li4v9cXFz/AAAA/wICAv8CAgL/AAAA/wAAAP8AAAD/AAAA/wAAAP8CAgL/ycnJ//////85OTn/AAAA/wQEBP8AAAD/Dw8P/+Pj4////////v7+/////////////////////////////v7+//z8/P///////f39/7Kysv9ZWVn/DAwM/wAAAP8DAwP/AQEB/wAAAP8AAAD/AAAA/wAAAP8CAgL/AAAA/zc3N////////////1paWv8AAAD/BwcH/wAAAP9fX1////////z8/P////////////////////////////39/f/8/Pz//////62trf8xMTH/AAAA/wAAAP8BAQH/AwMD/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wMDA/8AAAD/Wlpa////////////tbW1/wAAAP8GBgb/AAAA/5WVlf//////+/v7///////////////////////+/v7///////X19f9hYWH/AwMD/wAAAP8DAwP/BAQE/wEBAf8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AwMD/wAAAP+1tbX////////////7+/v/Ojo6/wAAAP8AAAD/mJiY///////7+/v//////////////////f39///////g4OD/KCgo/wAAAP8EBAT/AwMD/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wMDA/8AAAD/NjY2//v7+////////Pz8///////IyMj/AwMD/wAAAP+Ojo7///////v7+//////////////////9/f3//////2hoaP8AAAD/BwcH/wEBAf8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/AAAA/woKCv/W1tb///////39/f///////Pz8//////9/f3//AAAA/1RUVP///////Pz8/////////////v7+///////t7e3/EhIS/wAAAP8BAQH/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AQEB/wQEBP8AAAD/hoaG///////8/Pz//////////////////v7+//////9MTEz/AAAA/9zc3P///////f39///////+/v7//////+3t7f8SEhL/AAAA/wEBAf8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wEBAf8FBQX/AAAA/3Jycv///////Pz8///////////////////////9/f3//////+/v7/8oKCj/hISE///////8/Pz////////////+/v7//////05OTv8AAAD/BQUF/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wEBAf8EBAT/AgIC/wAAAP9YWFj/+/v7//7+/v/+/v7////////////////////////////+/v7///////Ly8v9sbGz/vr6+///////+/v7///////39/f//////0tLS/w4ODv8AAAD/BQUF/wMDA/8DAwP/AgIC/wQEBP8DAwP/AQEB/wAAAP8JCQn/kJCQ///////8/Pz////////////////////////////////////////////+/v7//v7+//39/f/BwcH/4ODg///////+/v7///////39/f//////ysrK/yAgIP8AAAD/AgIC/wAAAP8AAAD/AQEB/wAAAP8PDw//dnZ2/9XV1f//////+/v7//7+/v/////////////////////////////////////////////////+/v7//f39///////9/f3///////////////////////39/f//////6+vr/4yMjP88PDz/NjY2/zMzM/9UVFT/sbGx/+bm5v///////v7+//z8/P///////////////////////////////////////////////////////////////////////f39//////////////////////////////////z8/P/+/v7///////////////////////////////////////v7+//9/f3///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////7+/v/7+/v//f39//7+/v/+/v7//Pz8//v7+//9/f3/////////////////////////////////////////////////AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA="></td>
<td style="text-align:center" width="30pix"><img src="data:image/ico;base64,AAABAAEAICAAAAEAIACoEAAAFgAAACgAAAAgAAAAQAAAAAEAIAAAAAAAABAAAHQSAAB0EgAAAAAAAAAAAAD////////////////////////////////////////////////9/f3/+/v7//7+/v////////////////////////////////////////////39/f/8/Pz/////////////////////////////////////////////////////////////////////////////////////////////////////////////////9PT0/8/Pz/+kpKT/Wlpa/zo6Ov87Ozv/OTk5/4mJif/Gxsb/9PT0///////8/Pz///////////////////////////////////////////////////////////////////////////////////////7+/v//////1tbW/3l5ef8mJib/AAAA/wEBAf8AAAD/AAAA/wAAAP8AAAD/AgIC/wAAAP9LS0v/zs7O//j4+P/+/v7///////////////////////////////////////////////////////////////////////z8/P/7+/v/+Pj4//////+ysrL/AAAA/wEBAf8BAQH/AwMD/wQEBP8DAwP/AwMD/wMDA/8EBAT/AgIC/wMDA/8AAAD/dXV1///////8/Pz///////////////////////////////////////////////////////7+/v/8/Pz//////////////////f39//////+VlZX/AAAA/wICAv8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AwMD/wMDA/8AAAD/lpaW///////9/f3//f39//7+/v/////////////////////////////////+/v7//f39//////+jo6P/Xl5e/2hoaP9iYmL/eHh4/+zs7P9ubm7/AAAA/wICAv8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AgIC/wAAAP8VFRX/4uLi///////8/Pz//v7+//7+/v///////////////////////v7+///////x8fH/W1tb/wAAAP8CAgL/AAAA/wEBAf8AAAD/CQkJ/2ZmZv8SEhL/AAAA/wEBAf8AAAD/AAAA/wAA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AP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/AAAA/wgICP+zs7P///////z8/P//////8vLy/xgYGP8AAAD/AQEB/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wsLC/8mJib/FxcX/yIiIv9eXl7/wsLC///////8/Pz/////////////////LS0t/wAAAP8CAgL/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wEBAf8AAAD/EBAQ/29vb//BwcH/+/v7///////+/v7//f39/////////////Pz8//////9UVFT/AAAA/wMDA/8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/AAAA/wwMDP85OTn/eHh4/7Gxsf///////v7+///////7+/v//////66urv8AAAD/BAQE/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wEBAf8DAwP/AQEB/wICAv8AAAD/lJSU///////8/Pz////////////+/v7//////0NDQ/8AAAD/BQUF/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wEBAf8BAQH/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8GBgb/AAAA/1dXV////////v7+//////////////////39/f//////1NTU/xYWFv8AAAD/BAQE/wAAAP8AAAD/AAAA/wEBAf8AAAD/Ozs7/wYGBv8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/BQUF/wAAAP82Njb/6urq///////+/v7///////////////////////39/f//////2tra/yUlJf8AAAD/BAQE/wMDA/8BAQH/AwMD/wAAAP+MjIz/Nzc3/wAAAP8DAwP/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AgIC/wUFBf8AAAD/Ojo6/+rq6v///////f39//////////////////////////////////39/f//////9fX1/3R0dP8AAAD/AQEB/wEBAf8HBwf/AAAA/6Ghof/a2tr/BAQE/wAAAP8EBAT/AgIC/wEBAf8CAgL/AwMD/wMDA/8CAgL/AAAA/2ZmZv/7+/v//v7+//39/f////////////////////////////////////////////39/f/+/v7//////7m5uf9HR0f/BgYG/wMDA/8AAAD/lpaW//////+Xl5f/BAQE/wAAAP8BAQH/AAAA/wAAAP8BAQH/AAAA/xcXF/+ZmZn///////39/f/9/f3///////////////////////////////////////////////////////7+/v/8/Pz////////////e3t7/j4+P/yYmJv+lpaX////////////R0dH/Tk5O/ygoKP8TExP/MDAw/09PT/+rq6v/8PDw///////8/Pz//v7+///////////////////////////////////////////////////////////////////////8/Pz//Pz8/////////////Pz8//n5+f///////Pz8//7+/v//////+Pj4/+rq6v/7+/v////////////+/v7/+/v7////////////////////////////////////////////AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA="></td>
<td style="text-align:center" width="30pix"><img src="data:image/ico;base64,AAABAAEAICAAAAEAIACoEAAAFgAAACgAAAAgAAAAQAAAAAEAIAAAAAAAABAAAHQSAAB0EgAAAAAAAAAAAAD////////////////////////////////+/v7//v7+///////9/f3/19fX/8rKyv+np6f/sLCw/+vr6//m5ub/5ubm/+rq6v+ysrL/n5+f/8XFxf/d3d3//f39///////+/v7//v7+/////////////////////////////////////////////////////////////v7+///////+/v7/3Nzc/7Kysv/U1NT/+Pj4//39/f/l5eX/y8vL/9HR0f/R0dH/ysrK/+Xl5f/+/v7/9/f3/9nZ2f+0tLT/29vb//z8/P///////v7+//////////////////////////////////////////////////7+/v//////7Ozs/8DAwP/d3d3//////9zc3P94eHj/Kioq/wkJCf8AAAD/AAAA/wAAAP8AAAD/CQkJ/ysrK/9vb2//2NjY///////d3d3/t7e3/+3t7f///////v7+///////////////////////////////////////9/f3//////9ra2v+/v7///////9XV1f9NTU3/AQEB/wAAAP8AAAD/AQEB/wEBAf8BAQH/AQEB/wEBAf8BAQH/AAAA/wAAAP8CAgL/RUVF/8zMzP//////wMDA/9ra2v///////f39/////////////////////////////v7+///////h4eH/2NjY//////+CgoL/BAQE/wAAAP8CAgL/BAQE/wICAv8BAQH/AAAA/wAAAP8AAAD/AAAA/wEBAf8CAgL/BAQE/wICAv8AAAD/AQEB/4KCgv//////2NjY/+Hh4f///////v7+//////////////////7+/v//////3Nzc/9vb2//7+/v/X19f/wAAAP8EBAT/AwMD/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wMDA/8EBAT/AAAA/0tLS//5+fn/3Nzc/9zc3P///////v7+///////+/v7//////+jo6P/FxcX//////1dXV/8AAAD/BgYG/wEBAf8AAAD/AAAA/wAAAP8AAAD/AwMD/wQEBP8EBAT/BAQE/wQEBP8DAwP/AAAA/wAAAP8AAAD/AAAA/wEBAf8GBgb/AAAA/01NTf//////xsbG/+jo6P///////v7+///////9/f3/vb29//7+/v+AgID/AAAA/wYGBv8AAAD/AAAA/wAAAP8AAAD/AQEB/wMDA/8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8DAwP/AQEB/wAAAP8AAAD/AAAA/wAAAP8FBQX/AAAA/4GBgf/+/v7/vr6+//7+/v///////////+Li4v/l5eX/0NDQ/wUFBf8AAAD/AQEB/wAAAP8AAAD/AAAA/wEBAf8DAwP/AAAA/zY2Nv9/f3//oaGh/5+fn/+AgID/NjY2/wAAAP8DAwP/AQEB/wAAAP8AAAD/AAAA/wEBAf8CAgL/AQEB/8nJyf/m5ub/4uLi///////9/f3/0tLS//////9SUlL/AAAA/wMDA/8AAAD/AAAA/wAAAP8BAQH/AAAA/wsLC/+YmJj//f39///////////////////////8/Pz/oqKi/w0NDf8AAAD/BQUF/wQEBP8EBAT/BAQE/wcHB/8AAAD/RkZG///////T09P//Pz8/9/f3//q6ur/1NTU/wAAAP8BAQH/AAAA/wAAAP8AAAD/AQEB/wAAAP8KCgr/vLy8///////7+/v/+/v7//v7+//7+/v/+/v7//v7+///////xMTE/w8PD/8AAAD/AQEB/wAAAP8AAAD/AAAA/wEBAf8AAAD/ysrK/+vr6//f39//2NjY//////91dXX/AAAA/wMDA/8AAAD/AAAA/wAAAP8CAgL/AAAA/5ycnP//////+fn5//7+/v///////////////////////v7+//n5+f//////qqqq/1xcXP9oaGj/ZmZm/2ZmZv9mZmb/aGho/1xcXP+zs7P//Pz8/9nZ2f/BwcH//////zQ0NP8AAAD/AgIC/wAAAP8AAAD/AgIC/wAAAP8pKSn/+Pj4//r6+v/6+vr/+/v7//v7+//7+/v/+/v7//v7+//7+/v/+/v7//n5+f/9/f3///////////////////////////////////////7+/v/9/f3/wsLC/+Xl5f/l5eX/CQkJ/wAAAP8BAQH/AAAA/wAAAP8EBAT/AAAA/35+fv//////+/v7/////////////////////////////////////////////////////////////////////////////////////////////v7+///////d3d3/+/v7/8vLy/8AAAD/AQEB/wAAAP8AAAD/AAAA/wICAv8AAAD/aGho/6Kiov+Xl5f/mZmZ/5mZmf+ZmZn/mZmZ/5mZmf+ZmZn/mZmZ/5mZmf+ZmZn/mZmZ/5mZmf+ZmZn/mZmZ/5mZmf+ZmZn/mZmZ/5qamv+VlZX/6+vr//Pz8//i4uL/0dHR/wAAAP8BAQH/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AQEB/wAAAP/R0dH/4+Pj/+Pj4//R0dH/AAAA/wEBAf8AAAD/AAAA/wAAAP8AAAD/AAAA/wMDA/8ICAj/CAgI/wgICP8ICAj/CAgI/wgICP8ICAj/CAgI/wgICP8ICAj/CAgI/wgICP8FBQX/BAQE/wQEBP8EBAT/BAQE/wQEBP8FBQX/AAAA/9LS0v/i4uL/+vr6/8zMzP8AAAD/AQEB/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wEBAf8AAAD/zMzM//v7+//u7u7/4+Pj/wkJCf8AAAD/AQEB/wAAAP8AAAD/AgIC/wAAAP82Njb/o6Oj/5aWlv+ZmZn/mZmZ/5mZmf+ZmZn/mZmZ/5mZmf+ZmZn/mZmZ/5aWlv+jo6P/NTU1/wAAAP8CAgL/AAAA/wAAAP8BAQH/AAAA/wkJCf/k5OT/7u7u/8HBwf//////NjY2/wAAAP8DAwP/AAAA/wAAAP8BAQH/AAAA/xoaGv/w8PD///////7+/v/////////////////////////////////+/v7///////Dw8P8aGhr/AAAA/wEBAf8AAAD/AAAA/wMDA/8AAAD/Nzc3///////BwcH/3d3d//////97e3v/AAAA/wQEBP8AAAD/AAAA/wAAAP8EBAT/AAAA/25ubv//////9fX1//r6+v/7+/v/+/v7//v7+//7+/v/+fn5//b29v//////ZWVl/wAAAP8DAwP/AAAA/wAAAP8AAAD/BAQE/wAAAP+Ghob//////93d3f/j4+P/7Ozs/9TU1P8AAAD/AQEB/wAAAP8AAAD/AAAA/wAAAP8BAQH/AAAA/6Kiov///////Pz8//v7+//7+/v/+/v7//v7+//8/Pz//////5SUlP8AAAD/AQEB/wAAAP8AAAD/AAAA/wAAAP8AAAD/BQUF/9vb2//r6+v/4+Pj//r6+v/R0dH//////1JSUv8AAAD/AwMD/wAAAP8AAAD/AAAA/wEBAf8BAQH/AwMD/3Z2dv/09PT///////7+/v/+/v7//////+3t7f90dHT/AAAA/wICAv8AAAD/AAAA/wAAAP8AAAD/BAQE/wAAAP9bW1v//////9DQ0P/6+vr//////+Pj4//u7u7/z8/P/wUFBf8BAQH/AQEB/wAAAP8AAAD/AAAA/wEBAf8DAwP/AAAA/x8fH/9qamr/lpaW/5aWlv9qamr/HBwc/wAAAP8DAwP/AQEB/wAAAP8AAAD/AAAA/wEBAf8AAAD/CgoK/9XV1f/09PT/6enp/////////////Pz8/9PT0///////f39//wAAAP8FBQX/AAAA/wAAAP8AAAD/AAAA/wEBAf8DAwP/AAAA/wAAAP8AAAD/AAAA/wAAAP8BAQH/AwMD/wAAAP8AAAD/AAAA/wAAAP8BAQH/BAQE/wAAAP+Pj4///////9LS0v/8/Pz///////7+/v//////8fHx/97e3v//////Z2dn/wAAAP8GBgb/AQEB/wAAAP8AAAD/AAAA/wAAAP8CAgL/BAQE/wQEBP8EBAT/BAQE/wEBAf8AAAD/AAAA/wAAAP8AAAD/AQEB/wUFBf8AAAD/cXFx///////U1NT/7+/v///////+/v7///////7+/v//////6enp/+rq6v//////ZmZm/wAAAP8EBAT/AwMD/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AAAA/wAAAP8AAAD/AQEB/wQEBP8CAgL/AAAA/3Fxcf//////6enp/+rq6v////////////////////////////7+/v//////6+vr/+jo6P//////iYmJ/wYGBv8AAAD/AgIC/wQEBP8DAwP/AQEB/wAAAP8AAAD/AAAA/wAAAP8BAQH/AwMD/wQEBP8CAgL/AAAA/wkJCf+QkJD//////+jo6P/r6+v///////7+/v////////////////////////////7+/v//////7+/v/+Xl5f//////09PT/0tLS/8CAgL/AAAA/wAAAP8BAQH/AQEB/wEBAf8BAQH/AQEB/wEBAf8AAAD/AAAA/wQEBP9XV1f/4eHh///////l5eX/8PDw///////+/v7///////////////////////////////////////7+/v//////8/Pz/9LS0v/q6ur//////9jY2P9zc3P/Ly8v/wwMDP8AAAD/AAAA/wAAAP8AAAD/CwsL/zQ0NP+Dg4P/3d3d///////v7+//09PT//Pz8////////v7+//////////////////////////////////////////////////7+/v///////Pz8/+bm5v/T09P/7e3t//7+/v//////4+Pj/8nJyf/S0tL/0tLS/8nJyf/j4+P////////////s7Oz/0tLS/+vr6//7+/v///////7+/v////////////////////////////////////////////////////////////7+/v/+/v7///////v7+//n5+f/4uLi/8PDw//l5eX/9/f3/+Hh4f/h4eH/9/f3/+Xl5f/CwsL/4uLi/+fn5//7+/v///////7+/v/+/v7/////////////////////////////////AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA="></td>

</tr>
<tr>
<td>1.1 Altizure Earth </td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>

<tr>
<td>1.2 Openning </td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>1.3 Render items </td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>1.4 Altizure Moon </td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>1.5 Background </td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>2.1 Altizure project </td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>2.1.1 Project's water </td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>2.1.2 Project autoScale </td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>2.2 Tag</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>2.3 Polygon</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>2.4 Polyline </td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>2.5 Obj Model</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>2.5.1 Promoted Obj</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>2.6 Text Tag</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>2.7 Label Line</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>2.8 PolyCylinder</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>2.9 Canvas Tag</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>2.10 Light Beam</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>2.11 Zone</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>2.12 Particles</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>3.1 Mouse Events</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>3.2 Turn off events</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>4.1 Pickpoint on Earth</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>4.2 Pickpoint on project</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>4.3 Window to LngLatAlt</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>4.4 Window from LngLatAlt</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>4.5 LngLat to Alt</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=#ffdb9c></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=#b50804></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>4.6 Screenshot</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>4.7 Auto-adjust polygon</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=#b50804></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=#b50804></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>5.1 Camera pose</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>5.2 Camera flight</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>5.3 Camera range</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>5.4 Camera control</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>5.5 Camera matrix</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>5.6 Camera visualize</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>5.7 Camera Poses</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=#b50804></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>5.8 Visibility Analysis</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>5.9 Interactive Visibility</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>5.10 Look At</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>6.1 Crop project</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=#b50804></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr> 
<tr>
<td>6.2 Measure Volume</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=#ffdb9c></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>

<tr>
<td>6.3 Ditch</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=#b50804></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=#b50804></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>6.4 Objectation</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=#b50804></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=#ffdb9c></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>6.5 Marker Cluster</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=#b50804></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>6.6 Skyline Height limit</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=#b50804></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>6.7 Compute Overlap Area</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>7.1 Plugin GeoJson</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>7.2 Geo system</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=	#aaaaaa></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>10.1 Draw Polygon</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>10.2 Insert tag</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=	#aaaaaa></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>10.3 Div list</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
<tr>
<td>10.4 Interactive Crop</td>
<td bgcolor="ForestGreen"></td>
<td bgcolor=#b50804></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
<td bgcolor="ForestGreen"></td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th style="text-align:center">Legend</th>
</tr>
</thead>
<tbody>
<tr>
<td bgcolor="ForestGreen"></td>
<td>Fully support</td>
</tr>
<tr>
<td bgcolor=#ffdb9c></td>
<td>Can run but still have some problems</td>
</tr>
<tr>
<td bgcolor=#b50804></td>
<td>Can't run </td>
</tr>
<tr>
<td bgcolor=#aaaaaa></td>
<td>Unknow</td>
</tr>
</tbody>
</table>

Due to the limited browser performance and the interface provided, the complex and high-level parts of this demo cannot be run smoothly and correctly in IE11.0 and Safari.

In addition, the right mouse button drag event can be used to convert the view angle in the demo, but some browsers default right mouse button drag events are forward or backward of the web page, so the display effect may be affected in some browsers. These browsers are: UC, QQ, Sogou, 360 and 2345.