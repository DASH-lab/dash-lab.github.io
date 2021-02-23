

<p> SKKU AGC Anomaly Detection Dataset Page</p>

<h1 class="page-title">SKKU AGC Anomaly Detection Dataset</h1>
  <p>SKKU AGC Anomaly Detection Dataset은 다양한 장소에서 낮과 밤 모두에 대해 보행자가 내려다 보이는 높이에 카메라를 고정하여 촬영하였으며 Detection Data와 Classificaiton Data로 구성되어 있습니다. Adnomal event는 사람의 머리가 땅에 닿는 경우입니다.<p><br>
  
<h6><b>1. Detection Data</b></h6>
  <p>1920x1080 크기의 이미지와 anomaly label(.xml)로 구성되어 있으며, 이미지들은 day와 night 폴더에 있으며, label들은 day_anno, night_anno 폴더에 있습니다.</p>
  <p>day: 3000<br>night: 2000</p><br>

<h6><b>2. Classification Data</b></h6>
  <p>사람을 크롭한 이미지로 구성되어 있으며, nomal과 falldown의 두가지 클래스가 있습니다. 정상 이미지는 normal day와 normal night 폴더에 있고, falldown 이미지는 falldown_day와 falldown_night 폴더에 있습니다.</p>
  <p>normal_day: 3200<br>normal_night: 1300<br>falldown_day: 3700<br>falldown_night: 900</p>
  <br>
<p><b>Dataset Link</b></p>
  <a href="https://drive.google.com/drive/folders/1JfEMxKb70GSEEUKMBqr62UFOsMbpPK8s?usp=sharing">SKKU AGC Anomaly Detection Dataset</a><br><br>
<hr>
<p><b>Examples of Detection data</b></p>
<table>
  <tr>
    <td width="33%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_detection.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_detection3.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_detection4.jpg"></p>
    </td>
  </tr>
  <tr>
    <td width="33%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_detection1.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_detection2.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_detection5.jpg"></p>
    </td>
  </tr>
</table>
<br>
<hr>
<p><b>Examples of Classification data</b></p>
<table>
  <tr>
    <td width="33%" valign=top>
      <p align=center><img border=0  src="/img/AGC_classification.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0  src="/img/AGC_classification1.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0  src="/img/AGC_classification2.jpg"></p>
    </td>
  </tr>
  <tr>
    <td width="33%" valign=top>
      <p align=center><img border=0  src="/img/AGC_classification3.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0  src="/img/AGC_classification4.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0  src="/img/AGC_classification5.jpg"></p>
    </td>
  </tr>
</table>