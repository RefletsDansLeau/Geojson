<h1>①Nakano_ku_chouchoubetu3.json</h1>
<p>中野区85町丁別の境界データのgeojsonです。<br>ご自由にお使いください。ただし、コードを使って生じたいかなる問題にも責任を負いません。</p>
<p>データ元は、「（日本）政府統計の総合窓口（<a href="https://www.e-stat.go.jp/gis">ｅ－Ｓｔａｔ</a>）／地図で見る統計(統計GIS)／境界データ」でダウンロードしたShapeファイルを使用しています。</p>
<p>Shapeファイルをgeojsonデータに変換し、ファイルサイズを小さくするために、CITY_NAME、KEYCODE1、緯度経度以外を削除し「right-hand rule」ツールで変換しました。</p>
<p>[2020/10/4追記]Pythonのjson.loadで読み込めるように、町名を日本語→英語表記に変えました。</p>
<p>[2020/10/7追記] Python／folium／コロプレス図で色がつかない箇所があったので、KEYCODE1(行政コード)の数値のダブルクオテーションを取りました。</p>
<h1>②Nakano_ku_18chocho.json</h1>
<p>中野区18町別の境界データのgeojsonです。https://geojson.io/ で手書きしました。</p>
![image](https://user-images.githubusercontent.com/52129157/118077035-4cfa6a00-b3ee-11eb-8c5f-5d67946dacad.png)


<h2>行政コード（geoJSON内の“KEYCODE1”）は次の通りです。</h2>
<ul>
<li>	114001001	南台１丁目	</li>
<li>	114001002	南台２丁目	</li>
<li>	114001003	南台３丁目	</li>
<li>	114001004	南台４丁目	</li>
<li>	114001005	南台５丁目	</li>
<li>	114002001	弥生町１丁目	</li>
<li>	114002002	弥生町２丁目	</li>
<li>	114002003	弥生町３丁目	</li>
<li>	114002004	弥生町４丁目	</li>
<li>	114002005	弥生町５丁目	</li>
<li>	114002006	弥生町６丁目	</li>
<li>	114003001	本町１丁目	</li>
<li>	114003002	本町２丁目	</li>
<li>	114003003	本町３丁目	</li>
<li>	114003004	本町４丁目	</li>
<li>	114003005	本町５丁目	</li>
<li>	114003006	本町６丁目	</li>
<li>	114004001	中央１丁目	</li>
<li>	114004002	中央２丁目	</li>
<li>	114004003	中央３丁目	</li>
<li>	114004004	中央４丁目	</li>
<li>	114004005	中央５丁目	</li>
<li>	114005001	東中野１丁目	</li>
<li>	114005002	東中野２丁目	</li>
<li>	114005003	東中野３丁目	</li>
<li>	114005004	東中野４丁目	</li>
<li>	114005005	東中野５丁目	</li>
<li>	114006001	中野１丁目	</li>
<li>	114006002	中野２丁目	</li>
<li>	114006003	中野３丁目	</li>
<li>	114006004	中野４丁目	</li>
<li>	114006005	中野５丁目	</li>
<li>	114006006	中野６丁目	</li>
<li>	114007001	上高田１丁目	</li>
<li>	114007002	上高田２丁目	</li>
<li>	114007003	上高田３丁目	</li>
<li>	114007004	上高田４丁目	</li>
<li>	114007005	上高田５丁目	</li>
<li>	114008001	新井１丁目	</li>
<li>	114008002	新井２丁目	</li>
<li>	114008003	新井３丁目	</li>
<li>	114008004	新井４丁目	</li>
<li>	114008005	新井５丁目	</li>
<li>	114009001	沼袋１丁目	</li>
<li>	114009002	沼袋２丁目	</li>
<li>	114009003	沼袋３丁目	</li>
<li>	114009004	沼袋４丁目	</li>
<li>	114010001	松が丘１丁目	</li>
<li>	114010002	松が丘２丁目	</li>
<li>	114011001	江原町１丁目	</li>
<li>	114011002	江原町２丁目	</li>
<li>	114011003	江原町３丁目	</li>
<li>	114012001	江古田１丁目	</li>
<li>	114012002	江古田２丁目	</li>
<li>	114012003	江古田３丁目	</li>
<li>	114012004	江古田４丁目	</li>
<li>	114013001	丸山１丁目	</li>
<li>	114013002	丸山２丁目	</li>
<li>	114014001	野方１丁目	</li>
<li>	114014002	野方２丁目	</li>
<li>	114014003	野方３丁目	</li>
<li>	114014004	野方４丁目	</li>
<li>	114014005	野方５丁目	</li>
<li>	114014006	野方６丁目	</li>
<li>	114015001	大和町１丁目	</li>
<li>	114015002	大和町２丁目	</li>
<li>	114015003	大和町３丁目	</li>
<li>	114015004	大和町４丁目	</li>
<li>	114016001	若宮１丁目	</li>
<li>	114016002	若宮２丁目	</li>
<li>	114016003	若宮３丁目	</li>
<li>	114017001	白鷺１丁目	</li>
<li>	114017002	白鷺２丁目	</li>
<li>	114017003	白鷺３丁目	</li>
<li>	114018001	鷺宮１丁目	</li>
<li>	114018002	鷺宮２丁目	</li>
<li>	114018003	鷺宮３丁目	</li>
<li>	114018004	鷺宮４丁目	</li>
<li>	114018005	鷺宮５丁目	</li>
<li>	114018006	鷺宮６丁目	</li>
<li>	114019001	上鷺宮１丁目	</li>
<li>	114019002	上鷺宮２丁目	</li>
<li>	114019003	上鷺宮３丁目	</li>
<li>	114019004	上鷺宮４丁目	</li>
<li>	114019005	上鷺宮５丁目	</li>
</ul>
<li>114001	南台</li>
<li>114002	弥生町</li>
<li>114003	本町</li>
<li>114004	中央</li>
<li>114005	東中野</li>
<li>114006	中野</li>
<li>114007	上高田</li>
<li>114008	新井</li>
<li>114009	沼袋</li>
<li>114010	松が丘</li>
<li>114011	江原町</li>
<li>114012	江古田</li>
<li>114013	丸山</li>
<li>114014	野方</li>
<li>114015	大和町</li>
<li>114016	若宮</li>
<li>114017	白鷺</li>
<li>114018	鷺宮</li>
<li>114019	上鷺宮</li>
</ul>


<h2>作成のきっかけ</h2>
<p>子どもが多いエリアに保育園を誘致してほしいと思ったので、統計書で公開されている子どもの数をpythonで地図上に可視化してみようと思いました。町々別の境界データ（geoJSON）が無かったため、試行錯誤を重ねて整形しました。</p>

<h2>Pythonでコロプレス図を書く際のコード例(2020/12/31追記)</h2>
モジュールをインポートする。<br>
import folium<br>
import pandas as pd<br>
import json<br>

ex_data=pd.read_excel(' ./Nakano_data.xlsx')　人口データ(Excelファイル)を読み込む。<br>

json_open=open('nakano_ku_chouchoubetu3.json','r')<br>
nakano_geodata=json.load(json_open)　中野区の緯度・経度情報を開いて、読み込む。<br>

ここからベースとなる地図を描く。<br>
nakano_loc=[35.70,139.66]　地図の中心となる緯度経度を指定し(ここでは中野区)<br>
Nakano_choropleth=folium.Map(location=nakano_loc,zoom_start=13)　地図の尺度を指定<br>

ベースの地図にコロプレス図を重ねる<br>
folium.Choropleth(<br>
    geo_data=nakano_geodata,　　中野区町丁別境界データ<br>
    data=ex_data,　　　　　　　　色塗りの基準となるデータおよび行政コード<br>
    columns=['KEYCODE1','該当列'],　利用するエクセルの列名（行政コードと０歳人口）<br>
    key_on='feature.properties.KEYCODE1',　 geoJSONファイルの「行政コード」を指定<br>
    threshold_schale=[0,2000,4000,8000],　色の塗り分け指定<br>
    fill_color='YlGnBu',　塗りつぶしのカラーパレットの色<br>
    reset=True,<br>
    errors='ignore'<br>
).add_to(Nakano_choropleth)　　ベースの地図に加える<br>

Nakano_choropleth.save(outfile="./Nakanoku_choropleth.html")　htmlファイルで保存<br>

