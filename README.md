# huanghailong1217.github.io
屏幕像素适配原理

<h3>PX(CSS pixels)</h3> 
<p>虚拟像素：可以理解为“直觉”像素，CSS和JS使用的抽象单位，浏览器内的一切长度都是以CSS像素为单位的，CSS像素的单位是px。</p>
<h3>DP(device pixels) </h3> 
<p>设备像素：（也叫物理像素）显示器上最小的物理显示单元，有自己独立的色系，亮度。单位：pt</p>
<h3>DIP(Device independent Pixel)</h3> 
<p>设备独立像素：（也叫逻辑像素）可以认为是计算机坐标系中的一个点，这个点代表一个可以由程序使用的虚拟像素（css像素） css像素 = 设备独立像素</p>
<h3>DPR(device pixels ratio)</h3> 
<p>设备像素比：设备像素 / 设备独立像素；可通过window.devicePixelRatio获取</p>
