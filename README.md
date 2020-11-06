# OpenCV Windows Binaries

An index repository of prebuilt Windows binaries of OpenCV (Files stored at Google Drive and Cow Transfer).

一个预编译的Windows下的OpenCV索引仓库（文件主体在谷歌云盘和奶牛快传）。

<table>
    <thead align="center">
        <tr>
            <th>OpenCV</th>
            <th>CUDA</th>
            <th>cuDNN</th>
            <th>VC</th>
            <th>MKL</th>
            <th>TBB</th>
            <th>Python</th>
            <th>Library Type</th>
            <th>World</th>
            <th>Google Drive</th>
            <th nowrap="nowrap">奶牛快传</th>
            <th>Size</td>
        </tr>
    </thead>
    <tbody align="center">
        <tr>
            <td rowspan="6">4.4.0</td>
            <td rowspan="6">11.0</td>
            <td rowspan="6">8.0.2</td>
            <td rowspan="6">2019</td>
            <td rowspan="6">2020.2.254</td>
            <td rowspan="6">2020.2.216</td>
            <td rowspan="2">3.8.3</td>
            <td>Static</td>
            <td rowspan="2">Yes</td>
            <td><a href="https://drive.google.com/file/d/1479_1xUgsgOmCS9megSwXnLSsFF5sz9N/view?usp=sharing" title="cv2-Static.rar">:arrow_down:</a></td>
            <td><a href="https://mua.cowtransfer.com/s/fca034c1226d46" title="cv2-Static.rar">:arrow_down:</a></td>
            <td>61.95MB</td>
        </tr>
        <tr>
            <td>Dynamic</td>
            <td><a href="https://drive.google.com/file/d/1rN377fjTuoQZzJHJyUJa16fanmkpKa9d/view?usp=sharing" title="cv2-Dynamic.rar">:arrow_down:</a></td>
            <td><a href="https://mua.cowtransfer.com/s/c621276422eb48" title="cv2-Dynamic.rar">:arrow_down:</a></td>
            <td>2.45MB</td>
        </tr>
        <tr>
            <td rowspan="4">-</td>
            <td rowspan="2">Static</td>
            <td>No</td>
            <td><a href="https://drive.google.com/file/d/1WmCgZhxU3hFsLBi60e0Hk9DuGWnnUJiA/view?usp=sharing" title="OpenCV-4.4.0-Static.rar">:arrow_down:</a></td>
            <td><a href="https://mua.cowtransfer.com/s/eaeb2343f6ef40" title="OpenCV-4.4.0-Static.rar">:arrow_down:</a></td>
            <td>128.08MB</td>
        </tr>
        <tr>
            <td>Yes</td>
            <td><a href="https://drive.google.com/file/d/1AzdglooIj92CZOe7l_ena-X5SHtoOYFP/view?usp=sharing" title="OpenCV-4.4.0-Static-World.rar">:arrow_down:</a></td>
            <td><a href="https://mua.cowtransfer.com/s/4283c3597e2e4e" title="OpenCV-4.4.0-Static-World.rar">:arrow_down:</a></td>
            <td>129.01MB</td>
        </tr>
        <tr>
            <td rowspan="2">Dynamic</td>
            <td>No</td>
            <td><a href="https://drive.google.com/file/d/1fADWfjkQnADSw2jX6biaE9y2z_89Q7Y5/view?usp=sharing" title="OpenCV-4.4.0-Dynamic.rar">:arrow_down:</a></td>
            <td><a href="https://mua.cowtransfer.com/s/6d2ce1c452eb4f" title="OpenCV-4.4.0-Dynamic.rar">:arrow_down:</a></td>
            <td>67.70MB</td>
        </tr>
        <tr>
            <td>Yes</td>
            <td><a href="https://drive.google.com/file/d/1Tiz_3tHOAVWzRnLbjvlr2YDUNa4JHiNE/view?usp=sharing" title="OpenCV-4.4.0-Dynamic-World.rar">:arrow_down:</a></td>
            <td><a href="https://mua.cowtransfer.com/s/072b6291982249" title="OpenCV-4.4.0-Dynamic-World.rar">:arrow_down:</a></td>
            <td>66.14MB</td>
        </tr>
    </tbody>
</table>

## Usage

1. Extract files to ***Python Install Path\\Lib\\site-packages\\cv2***.

   解压文件到***Python安装目录\\Lib\\site-packages\\cv2***下。

2. You **MUST** install TBB and may need put **tbb.dll** in your system Path. For Python, if PATH not works, put it in the same directory as ***cv2.x.pyd***.

   你**必须**安装TBB，可能也需要把**tbb.dll**放在系统环境变量的路径（Path）下。Python的环境变量如果查找不到它，请放到和***cv2.x.pyd***同目录下。

3. MKL is neccessary for dynamic libraries or Python packages. You may also need put MKL related dynamic libraries like ***mkl_tbb_thread.dll*** in your system Path. For Python, if PATH not works, put them in the same directory as ***cv2.x.pyd***.

   动态库或Python包必须安装MKL。可能也需要把诸如***mkl_tbb_thread.dll***等MKL相关的动态库放到系统环境变量的路径（Path）下。Python的环境变量如果查找不到它，请放到和***cv2.x.pyd***同目录下。
