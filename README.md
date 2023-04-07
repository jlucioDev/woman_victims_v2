## Modelo de Decisão Multicritério para classificar municípios quanto ao risco de violência doméstica contra a mulher: um estudo a partir da Amazônia Paraense.

#### A violência doméstica contra a mulher (VDCM) se constitui em uma das mais sérias questões de saúde pública local e global, exigindo o enfrentamento por meio de políticas públicas efetivas. Assim, o objetivo deste projeto é apresentar um modelo de análise de decisão multicritério (MCDA) baseado no ELECTRE Tri-B para classificar os municípios do estado do Pará de acordo com o risco à violência doméstica contra as mulheres em seus territórios de modo a mapeá-los em ordem decrescente quanto a esse risco. Propõe-se um modelo que considera entre os critérios de análise e classificação a existência de equipamentos de apoio e proteção à mulher nesses municípios, bem como seus indicadores socioeconômicos. Os resultados mostraram que, em municípios com menor risco de VDCM, há equipamentos de proteção, bons indicadores socioeconômicos, mas alta taxa de denúncias, corroborando a máxima de que ambientes com mais mecanismos de proteção à mulher propiciam maior número de denúncias. Assim, a metodologia empregada permitiu a identificação dos municípios em que há maior risco de VDCM, o mapeamento desses municípios e regiões possibilitando ações focadas e com mais possibilidade de serem eficazes no combate e prevenção à VDCM.

## 🚀 Tecnologias Utilizadas


> Pandas 
Download the latest version at https://pandas.pydata.org/
```python
pip install pandas
```

> Requests
The latest version at https://pypi.org/project/requests/
```python
pip install requests
```

> PyDecision
The latest version at https://pypi.org/project/pyDecision/
```python
pip install pyDecision
```

> GeoPandas
The latest version at https://geopandas.org/en/stable/
```python
pip install geopandas
```

## Mapa Interativo

<img src="Imagens\Mapa_interativo_GIF.gif?raw=true" width="800px">

Acesse e teste o mapa interativo [aqui](https://jluciodev.github.io/woman_victims_v2/)


## Tabela de Classificação

Resultado Geral da classificação dos municípios utilizando o método MCDM ELECTRE Tri-b.

<table class="table table-bordered table-hover table-condensed">
<thead><tr><th title="Field #1">Index</th>
<th title="Field #2">id</th>
<th title="Field #3">localidade</th>
<th title="Field #4">IAP</th>
<th title="Field #5">IDH</th>
<th title="Field #6">PIB</th>
<th title="Field #7">GINI</th>
<th title="Field #8">Classe</th>
<th title="Field #9">Qtd de Denuncias</th>
</tr></thead>
<tbody><tr>
<td>x1</td>
<td align="right">150010</td>
<td>Abaetetuba</td>
<td>1.6550352213773933</td>
<td>0.872794460337242</td>
<td>-0.28396057685100556</td>
<td>-1.0517172529984826</td>
<td align="right">1</td>
<td align="right">77</td>
</tr>
<tr>
<td>x2</td>
<td align="right">150013</td>
<td>Abel Figueiredo</td>
<td>0.009898072981534015</td>
<td>0.7647096737863871</td>
<td>0.19959906413553086</td>
<td>0.2429026558860896</td>
<td align="right">2</td>
<td align="right">0</td>
</tr>
<tr>
<td>x3</td>
<td align="right">150020</td>
<td>Acará</td>
<td>0.8938074348664315</td>
<td>-1.2887891393638802</td>
<td>0.3932961272898631</td>
<td>0.6045853465832371</td>
<td align="right">2</td>
<td align="right">11</td>
</tr>
<tr>
<td>x4</td>
<td align="right">150030</td>
<td>Afuá</td>
<td>0.8938074348664315</td>
<td>-1.639976270133218</td>
<td>-0.2987334648698611</td>
<td>-0.6508373064444771</td>
<td align="right">2</td>
<td align="right">1</td>
</tr>
<tr>
<td>x5</td>
<td align="right">150034</td>
<td>Água Azul do Norte</td>
<td>0.009898072981534015</td>
<td>-0.2690661378543141</td>
<td>0.6291232461730532</td>
<td>0.2429026558860896</td>
<td align="right">2</td>
<td align="right">4</td>
</tr>
<tr>
<td>x6</td>
<td align="right">150040</td>
<td>Alenquer</td>
<td>-1.3899782178749143</td>
<td>-0.2690661378543141</td>
<td>-0.10459047225306266</td>
<td>-0.6508373064444771</td>
<td align="right">3</td>
<td align="right">8</td>
</tr>
<tr>
<td>x7</td>
<td align="right">150050</td>
<td>Almeirim</td>
<td>-1.3899782178749143</td>
<td>1.0760621669753159</td>
<td>0.6414125882564761</td>
<td>-5.199337582605575</td>
<td align="right">3</td>
<td align="right">5</td>
</tr>
<tr>
<td>x8</td>
<td align="right">150060</td>
<td>Altamira</td>
<td>-1.3899782178749143</td>
<td>1.3996566480498198</td>
<td>1.1846350648209882</td>
<td>-1.0517172529984826</td>
<td align="right">1</td>
<td align="right">14</td>
</tr>
<tr>
<td>x9</td>
<td align="right">150070</td>
<td>Anajás</td>
<td>0.009898072981534015</td>
<td>-1.740243655445895</td>
<td>-1.2492821482286744</td>
<td>0.6045853465832371</td>
<td align="right">3</td>
<td align="right">0</td>
</tr>
<tr>
<td>x10</td>
<td align="right">150080</td>
<td>Ananindeua</td>
<td>1.5915563484056177</td>
<td>2.3396138240482443</td>
<td>0.5952319253384546</td>
<td>-0.20396117575131423</td>
<td align="right">0</td>
<td align="right">237</td>
</tr>
<tr>
<td>x11</td>
<td align="right">150085</td>
<td>Anapu</td>
<td>-1.3899782178749143</td>
<td>-0.5744599931693578</td>
<td>0.5341837998386836</td>
<td>-1.0517172529984826</td>
<td align="right">3</td>
<td align="right">10</td>
</tr>
<tr>
<td>x12</td>
<td align="right">150090</td>
<td>Augusto Corrêa</td>
<td>0.009898072981534015</td>
<td>-1.0573264128118767</td>
<td>-1.5350067026256073</td>
<td>-1.0517172529984826</td>
<td align="right">3</td>
<td align="right">6</td>
</tr>
<tr>
<td>x13</td>
<td align="right">150095</td>
<td>Aurora do Pará</td>
<td>-1.3899782178749143</td>
<td>-1.0748804789931632</td>
<td>-1.5743125794328128</td>
<td>0.6045853465832371</td>
<td align="right">3</td>
<td align="right">3</td>
</tr>
<tr>
<td>x14</td>
<td align="right">150100</td>
<td>Aveiro</td>
<td>0.009898072981534015</td>
<td>-0.8088444041133962</td>
<td>-1.0452882099872884</td>
<td>0.6045853465832371</td>
<td align="right">3</td>
<td align="right">3</td>
</tr>
<tr>
<td>x15</td>
<td align="right">150110</td>
<td>Bagre</td>
<td>-0.6886512391544619</td>
<td>-1.9875447386038565</td>
<td>-2.0105659293606544</td>
<td>0.2429026558860896</td>
<td align="right">3</td>
<td align="right">3</td>
</tr>
<tr>
<td>x16</td>
<td align="right">150120</td>
<td>Baião</td>
<td>0.009898072981534015</td>
<td>-0.08832777795737361</td>
<td>-0.1279851077090356</td>
<td>0.2429026558860896</td>
<td align="right">2</td>
<td align="right">8</td>
</tr>
<tr>
<td>x17</td>
<td align="right">150125</td>
<td>Bannach</td>
<td>-1.3899782178749143</td>
<td>0.2954151418352379</td>
<td>1.2170528775798555</td>
<td>-0.20396117575131423</td>
<td align="right">2</td>
<td align="right">1</td>
</tr>
<tr>
<td>x18</td>
<td align="right">150130</td>
<td>Barcarena</td>
<td>1.9742932230425354</td>
<td>1.3300503471619685</td>
<td>1.7251917919153636</td>
<td>-1.4705452438880622</td>
<td align="right">0</td>
<td align="right">65</td>
</tr>
<tr>
<td>x19</td>
<td align="right">150140</td>
<td>Belém</td>
<td>1.5915563484056177</td>
<td>5.19933758270342</td>
<td>1.052815819551034</td>
<td>-2.166106752892329</td>
<td align="right">0</td>
<td align="right">958</td>
</tr>
<tr>
<td>x20</td>
<td align="right">150145</td>
<td>Belterra</td>
<td>-1.3899782178749143</td>
<td>0.11418529432142852</td>
<td>-0.32512258678455064</td>
<td>1.4705452438880622</td>
<td align="right">3</td>
<td align="right">0</td>
</tr>
<tr>
<td>x21</td>
<td align="right">150150</td>
<td>Benevides</td>
<td>0.7049775102792363</td>
<td>1.3996566480498198</td>
<td>1.2485415961917203</td>
<td>0.2429026558860896</td>
<td align="right">1</td>
<td align="right">18</td>
</tr>
<tr>
<td>x22</td>
<td align="right">150157</td>
<td>Bom Jesus do Tocantins</td>
<td>0.3374821867256964</td>
<td>0.16532666916589714</td>
<td>-0.06266557194917585</td>
<td>-1.0517172529984826</td>
<td align="right">2</td>
<td align="right">2</td>
</tr>
<tr>
<td>x23</td>
<td align="right">150160</td>
<td>Bonito</td>
<td>-0.6886512391544619</td>
<td>-0.6985257103450601</td>
<td>-0.1641535737192016</td>
<td>5.19933758270342</td>
<td align="right">1</td>
<td align="right">3</td>
</tr>
<tr>
<td>x24</td>
<td align="right">150170</td>
<td>Bragança</td>
<td>0.009898072981534015</td>
<td>0.45498114030642833</td>
<td>-0.34742692727923885</td>
<td>-0.20396117575131423</td>
<td align="right">2</td>
<td align="right">29</td>
</tr>
<tr>
<td>x25</td>
<td align="right">150172</td>
<td>Brasil Novo</td>
<td>0.3374821867256964</td>
<td>0.6644777254117699</td>
<td>0.7783946738713903</td>
<td>0.967421566101701</td>
<td align="right">1</td>
<td align="right">1</td>
</tr>
<tr>
<td>x26</td>
<td align="right">150175</td>
<td>Brejo Grande do Araguaia</td>
<td>-1.3899782178749143</td>
<td>0.21690442598171078</td>
<td>0.06094385635407057</td>
<td>-0.20396117575131423</td>
<td align="right">3</td>
<td align="right">2</td>
</tr>
<tr>
<td>x27</td>
<td align="right">150178</td>
<td>Breu Branco</td>
<td>0.009898072981534015</td>
<td>-0.21690442598171064</td>
<td>-0.3521853998386554</td>
<td>-0.20396117575131423</td>
<td align="right">3</td>
<td align="right">6</td>
</tr>
<tr>
<td>x28</td>
<td align="right">150180</td>
<td>Breves</td>
<td>1.5915563484056177</td>
<td>-1.3996566480498192</td>
<td>-0.8057617781468005</td>
<td>-1.0517172529984826</td>
<td align="right">2</td>
<td align="right">12</td>
</tr>
<tr>
<td>x29</td>
<td align="right">150190</td>
<td>Bujaru</td>
<td>1.4813016392052942</td>
<td>-0.48699393885129033</td>
<td>0.4582270080444341</td>
<td>-0.20396117575131423</td>
<td align="right">1</td>
<td align="right">11</td>
</tr>
<tr>
<td>x30</td>
<td align="right">150195</td>
<td>Cachoeira do Piriá</td>
<td>-1.3899782178749143</td>
<td>-1.9404374900135768</td>
<td>-5.199337582605575</td>
<td>0.967421566101701</td>
<td align="right">3</td>
<td align="right">1</td>
</tr>
<tr>
<td>x31</td>
<td align="right">150200</td>
<td>Cachoeira do Arari</td>
<td>1.395418154614277</td>
<td>-0.6985257103450601</td>
<td>-0.5774096666123206</td>
<td>-0.6508373064444771</td>
<td align="right">2</td>
<td align="right">3</td>
</tr>
<tr>
<td>x32</td>
<td align="right">150210</td>
<td>Cametá</td>
<td>0.009898072981534015</td>
<td>-0.11418529432142824</td>
<td>-0.6743562933573027</td>
<td>-0.6508373064444771</td>
<td align="right">3</td>
<td align="right">16</td>
</tr>
<tr>
<td>x33</td>
<td align="right">150215</td>
<td>Canaã dos Carajás</td>
<td>0.3374821867256964</td>
<td>1.7460165226992137</td>
<td>5.19933758270342</td>
<td>0.6045853465832371</td>
<td align="right">0</td>
<td align="right">14</td>
</tr>
<tr>
<td>x34</td>
<td align="right">150220</td>
<td>Capanema</td>
<td>1.6550352213773933</td>
<td>1.2154478208330304</td>
<td>0.661713667133729</td>
<td>-0.20396117575131423</td>
<td align="right">1</td>
<td align="right">25</td>
</tr>
<tr>
<td>x35</td>
<td align="right">150230</td>
<td>Capitão Poço</td>
<td>0.3374821867256964</td>
<td>-0.5744599931693578</td>
<td>0.32413646555592684</td>
<td>-0.6508373064444771</td>
<td align="right">2</td>
<td align="right">5</td>
</tr>
<tr>
<td>x36</td>
<td align="right">150240</td>
<td>Castanhal</td>
<td>1.9742932230425354</td>
<td>1.7460165226992137</td>
<td>0.867179887825617</td>
<td>-0.6508373064444771</td>
<td align="right">0</td>
<td align="right">94</td>
</tr>
<tr>
<td>x37</td>
<td align="right">150250</td>
<td>Chaves</td>
<td>0.8938074348664315</td>
<td>-2.150833398799841</td>
<td>-0.704008408610483</td>
<td>1.4705452438880622</td>
<td align="right">2</td>
<td align="right">1</td>
</tr>
<tr>
<td>x38</td>
<td align="right">150260</td>
<td>Colares</td>
<td>0.7049775102792363</td>
<td>0.501297710767729</td>
<td>-1.6432252209245173</td>
<td>5.19933758270342</td>
<td align="right">1</td>
<td align="right">3</td>
</tr>
<tr>
<td>x39</td>
<td align="right">150270</td>
<td>Conceição do Araguaia</td>
<td>0.7049775102792363</td>
<td>1.0299567622253682</td>
<td>0.2048688891943126</td>
<td>-2.166106752892329</td>
<td align="right">1</td>
<td align="right">4</td>
</tr>
<tr>
<td>x40</td>
<td align="right">150275</td>
<td>Concórdia do Pará</td>
<td>0.3374821867256964</td>
<td>-0.2500034634399197</td>
<td>-0.45693201945496076</td>
<td>-0.20396117575131423</td>
<td align="right">3</td>
<td align="right">10</td>
</tr>
<tr>
<td>x41</td>
<td align="right">150276</td>
<td>Cumaru do Norte</td>
<td>1.395418154614277</td>
<td>-0.517723552817668</td>
<td>1.0137110662812332</td>
<td>1.4705452438880622</td>
<td align="right">1</td>
<td align="right">0</td>
</tr>
<tr>
<td>x42</td>
<td align="right">150277</td>
<td>Curionópolis</td>
<td>0.3374821867256964</td>
<td>0.9535455948356467</td>
<td>1.8905199701913757</td>
<td>-0.6508373064444771</td>
<td align="right">1</td>
<td align="right">5</td>
</tr>
<tr>
<td>x43</td>
<td align="right">150280</td>
<td>Curralinho</td>
<td>-1.3899782178749143</td>
<td>-1.4711298483814719</td>
<td>-1.1612271010375588</td>
<td>-0.6508373064444771</td>
<td align="right">3</td>
<td align="right">14</td>
</tr>
<tr>
<td>x44</td>
<td align="right">150285</td>
<td>Curuá</td>
<td>0.009898072981534015</td>
<td>-0.08832777795737361</td>
<td>-0.39086951563046374</td>
<td>1.4705452438880622</td>
<td align="right">2</td>
<td align="right">2</td>
</tr>
<tr>
<td>x45</td>
<td align="right">150290</td>
<td>Curuçá</td>
<td>-1.3899782178749143</td>
<td>-0.012660076940314008</td>
<td>-1.332324422320661</td>
<td>-0.20396117575131423</td>
<td align="right">3</td>
<td align="right">13</td>
</tr>
<tr>
<td>x46</td>
<td align="right">150293</td>
<td>Dom Eliseu</td>
<td>0.009898072981534015</td>
<td>0.6985257103450605</td>
<td>0.0655948100033045</td>
<td>-0.20396117575131423</td>
<td align="right">2</td>
<td align="right">4</td>
</tr>
<tr>
<td>x47</td>
<td align="right">150295</td>
<td>Eldorado do Carajás</td>
<td>-0.18936960178047132</td>
<td>-0.3931021616736824</td>
<td>0.29766933194685025</td>
<td>-1.0517172529984826</td>
<td align="right">3</td>
<td align="right">5</td>
</tr>
<tr>
<td>x48</td>
<td align="right">150300</td>
<td>Faro</td>
<td>-1.3899782178749143</td>
<td>-0.3219708901819884</td>
<td>-0.6056907889232116</td>
<td>-0.6508373064444771</td>
<td align="right">3</td>
<td align="right">0</td>
</tr>
<tr>
<td>x49</td>
<td align="right">150304</td>
<td>Floresta do Araguaia</td>
<td>0.009898072981534015</td>
<td>0.02488550311706342</td>
<td>0.3763263266247551</td>
<td>0.2429026558860896</td>
<td align="right">2</td>
<td align="right">1</td>
</tr>
<tr>
<td>x50</td>
<td align="right">150307</td>
<td>Garrafão do Norte</td>
<td>0.3374821867256964</td>
<td>-0.9859472039535683</td>
<td>-0.5416440457343273</td>
<td>0.6045853465832371</td>
<td align="right">3</td>
<td align="right">4</td>
</tr>
<tr>
<td>x51</td>
<td align="right">150309</td>
<td>Goianésia do Pará</td>
<td>-1.3899782178749143</td>
<td>-0.3931021616736824</td>
<td>-0.5157552750619329</td>
<td>-0.20396117575131423</td>
<td align="right">3</td>
<td align="right">3</td>
</tr>
<tr>
<td>x52</td>
<td align="right">150310</td>
<td>Gurupá</td>
<td>0.3374821867256964</td>
<td>-1.2164605669458162</td>
<td>-0.558765250469268</td>
<td>-0.20396117575131423</td>
<td align="right">3</td>
<td align="right">6</td>
</tr>
<tr>
<td>x53</td>
<td align="right">150320</td>
<td>Igarapé-Açu</td>
<td>0.009898072981534015</td>
<td>0.348755695517045</td>
<td>-0.43087805244480715</td>
<td>0.6045853465832371</td>
<td align="right">2</td>
<td align="right">10</td>
</tr>
<tr>
<td>x54</td>
<td align="right">150330</td>
<td>Igarapé-Miri</td>
<td>-1.3899782178749143</td>
<td>-0.6352697098765964</td>
<td>-0.6470615234966506</td>
<td>-0.20396117575131423</td>
<td align="right">3</td>
<td align="right">16</td>
</tr>
<tr>
<td>x55</td>
<td align="right">150340</td>
<td>Inhangapi</td>
<td>0.3374821867256964</td>
<td>-0.17745000830524024</td>
<td>-0.06659007316642435</td>
<td>1.4705452438880622</td>
<td align="right">2</td>
<td align="right">3</td>
</tr>
<tr>
<td>x56</td>
<td align="right">150345</td>
<td>Ipixuna do Pará</td>
<td>-1.3899782178749143</td>
<td>-1.639976270133218</td>
<td>-0.38897763426879584</td>
<td>0.2429026558860896</td>
<td align="right">3</td>
<td align="right">4</td>
</tr>
<tr>
<td>x57</td>
<td align="right">150350</td>
<td>Irituia</td>
<td>0.009898072981534015</td>
<td>-0.4178506199571618</td>
<td>-1.8240928287178853</td>
<td>0.2429026558860896</td>
<td align="right">3</td>
<td align="right">6</td>
</tr>
<tr>
<td>x58</td>
<td align="right">150360</td>
<td>Itaituba</td>
<td>1.395418154614277</td>
<td>1.0299567622253682</td>
<td>0.8720868495199047</td>
<td>-1.4705452438880622</td>
<td align="right">1</td>
<td align="right">20</td>
</tr>
<tr>
<td>x59</td>
<td align="right">150370</td>
<td>Itupiranga</td>
<td>0.3374821867256964</td>
<td>-0.9613197165146152</td>
<td>0.01931445271383316</td>
<td>0.2429026558860896</td>
<td align="right">3</td>
<td align="right">4</td>
</tr>
<tr>
<td>x60</td>
<td align="right">150375</td>
<td>Jacareacanga</td>
<td>0.3374821867256964</td>
<td>-1.3278539211951115</td>
<td>1.9871079126086828</td>
<td>1.4705452438880622</td>
<td align="right">1</td>
<td align="right">0</td>
</tr>
<tr>
<td>x61</td>
<td align="right">150380</td>
<td>Jacundá</td>
<td>0.3374821867256964</td>
<td>0.7647096737863871</td>
<td>-0.6655827292846832</td>
<td>-0.20396117575131423</td>
<td align="right">2</td>
<td align="right">6</td>
</tr>
<tr>
<td>x62</td>
<td align="right">150390</td>
<td>Juruti</td>
<td>1.5915563484056177</td>
<td>0.24701054331715394</td>
<td>0.9289481729531123</td>
<td>-0.6508373064444771</td>
<td align="right">1</td>
<td align="right">5</td>
</tr>
<tr>
<td>x63</td>
<td align="right">150400</td>
<td>Limoeiro do Ajuru</td>
<td>-1.3899782178749143</td>
<td>-0.8088444041133962</td>
<td>0.5053298981796477</td>
<td>1.4705452438880622</td>
<td align="right">3</td>
<td align="right">3</td>
</tr>
<tr>
<td>x64</td>
<td align="right">150405</td>
<td>Mãe do Rio</td>
<td>0.8938074348664315</td>
<td>0.4367664924616709</td>
<td>-0.20926760156612093</td>
<td>-0.20396117575131423</td>
<td align="right">2</td>
<td align="right">15</td>
</tr>
<tr>
<td>x65</td>
<td align="right">150410</td>
<td>Magalhães Barata</td>
<td>-0.6886512391544619</td>
<td>0.39866393514661336</td>
<td>-0.47827196714884584</td>
<td>0.967421566101701</td>
<td align="right">3</td>
<td align="right">0</td>
</tr>
<tr>
<td>x66</td>
<td align="right">150420</td>
<td>Marabá</td>
<td>2.149556255327738</td>
<td>1.5140418080574354</td>
<td>1.6796278123214226</td>
<td>-1.4705452438880622</td>
<td align="right">0</td>
<td align="right">106</td>
</tr>
<tr>
<td>x67</td>
<td align="right">150430</td>
<td>Maracanã</td>
<td>0.3374821867256964</td>
<td>-0.19608582502158148</td>
<td>-0.9006024469265341</td>
<td>-0.20396117575131423</td>
<td align="right">3</td>
<td align="right">10</td>
</tr>
<tr>
<td>x68</td>
<td align="right">150440</td>
<td>Marapanim</td>
<td>0.009898072981534015</td>
<td>0.6352697098765966</td>
<td>-0.8718186709900424</td>
<td>0.967421566101701</td>
<td align="right">2</td>
<td align="right">10</td>
</tr>
<tr>
<td>x69</td>
<td align="right">150442</td>
<td>Marituba</td>
<td>0.8938074348664315</td>
<td>1.8834269552345257</td>
<td>0.51620614513781</td>
<td>0.6045853465832371</td>
<td align="right">1</td>
<td align="right">48</td>
</tr>
<tr>
<td>x70</td>
<td align="right">150445</td>
<td>Medicilândia</td>
<td>0.009898072981534015</td>
<td>-0.012660076940314008</td>
<td>0.9075663413953473</td>
<td>0.2429026558860896</td>
<td align="right">2</td>
<td align="right">1</td>
</tr>
<tr>
<td>x71</td>
<td align="right">150450</td>
<td>Melgaço</td>
<td>0.009898072981534015</td>
<td>-2.335964602222785</td>
<td>-2.1134285903883736</td>
<td>5.19933758270342</td>
<td align="right">3</td>
<td align="right">8</td>
</tr>
<tr>
<td>x72</td>
<td align="right">150460</td>
<td>Mocajuba</td>
<td>0.009898072981534015</td>
<td>-0.1427514437549462</td>
<td>0.26001578412885173</td>
<td>-1.7460165226992128</td>
<td align="right">2</td>
<td align="right">2</td>
</tr>
<tr>
<td>x73</td>
<td align="right">150470</td>
<td>Moju</td>
<td>-1.3899782178749143</td>
<td>-0.6352697098765964</td>
<td>0.09515050622658876</td>
<td>0.2429026558860896</td>
<td align="right">3</td>
<td align="right">16</td>
</tr>
<tr>
<td>x74</td>
<td align="right">150480</td>
<td>Monte Alegre</td>
<td>0.009898072981534015</td>
<td>-5.199337582605575</td>
<td>-0.018641185710635444</td>
<td>-0.6508373064444771</td>
<td align="right">3</td>
<td align="right">8</td>
</tr>
<tr>
<td>x75</td>
<td align="right">150490</td>
<td>Muaná</td>
<td>0.3374821867256964</td>
<td>-0.6352697098765964</td>
<td>-1.2986906135451495</td>
<td>0.2429026558860896</td>
<td align="right">3</td>
<td align="right">4</td>
</tr>
<tr>
<td>x76</td>
<td align="right">150495</td>
<td>Nova Esperança do Piriá</td>
<td>0.3374821867256964</td>
<td>-1.4711298483814719</td>
<td>-0.194423988940204</td>
<td>1.4705452438880622</td>
<td align="right">3</td>
<td align="right">4</td>
</tr>
<tr>
<td>x77</td>
<td align="right">150497</td>
<td>Nova Ipixuna</td>
<td>-1.3899782178749143</td>
<td>-0.037988351230282213</td>
<td>-0.26710192665384747</td>
<td>-1.7460165226992128</td>
<td align="right">3</td>
<td align="right">0</td>
</tr>
<tr>
<td>x78</td>
<td align="right">150500</td>
<td>Nova Timboteua</td>
<td>0.3374821867256964</td>
<td>0.6352697098765966</td>
<td>-1.0133368679006982</td>
<td>0.967421566101701</td>
<td align="right">2</td>
<td align="right">4</td>
</tr>
<tr>
<td>x79</td>
<td align="right">150503</td>
<td>Novo Progresso</td>
<td>0.009898072981534015</td>
<td>1.7460165226992137</td>
<td>1.389392740919949</td>
<td>1.4705452438880622</td>
<td align="right">0</td>
<td align="right">2</td>
</tr>
<tr>
<td>x80</td>
<td align="right">150506</td>
<td>Novo Repartimento</td>
<td>0.3374821867256964</td>
<td>-0.8741359098836601</td>
<td>0.03372946789822882</td>
<td>-1.0517172529984826</td>
<td align="right">3</td>
<td align="right">3</td>
</tr>
<tr>
<td>x81</td>
<td align="right">150510</td>
<td>Óbidos</td>
<td>1.5915563484056177</td>
<td>0.2954151418352379</td>
<td>0.8011453213279762</td>
<td>-0.20396117575131423</td>
<td align="right">1</td>
<td align="right">1</td>
</tr>
<tr>
<td>x82</td>
<td align="right">150520</td>
<td>Oeiras do Pará</td>
<td>-0.6886512391544619</td>
<td>-1.259039028026586</td>
<td>0.16143512853700098</td>
<td>0.967421566101701</td>
<td align="right">3</td>
<td align="right">4</td>
</tr>
<tr>
<td>x83</td>
<td align="right">150530</td>
<td>Oriximiná</td>
<td>1.119908308935073</td>
<td>0.8011340080975516</td>
<td>1.5384495552156037</td>
<td>-1.0517172529984826</td>
<td align="right">1</td>
<td align="right">2</td>
</tr>
<tr>
<td>x84</td>
<td align="right">150540</td>
<td>Ourém</td>
<td>0.3374821867256964</td>
<td>-0.21690442598171064</td>
<td>-0.1701011827138371</td>
<td>0.6045853465832371</td>
<td align="right">2</td>
<td align="right">1</td>
</tr>
<tr>
<td>x85</td>
<td align="right">150543</td>
<td>Ourilândia do Norte</td>
<td>-1.3899782178749143</td>
<td>0.8181874703636373</td>
<td>0.8245993304597683</td>
<td>-0.20396117575131423</td>
<td align="right">2</td>
<td align="right">2</td>
</tr>
<tr>
<td>x86</td>
<td align="right">150548</td>
<td>Pacajá</td>
<td>0.3374821867256964</td>
<td>-1.1202053547494892</td>
<td>0.4562670341869378</td>
<td>-1.0517172529984826</td>
<td align="right">2</td>
<td align="right">2</td>
</tr>
<tr>
<td>x87</td>
<td align="right">150549</td>
<td>Palestina do Pará</td>
<td>-1.3899782178749143</td>
<td>0.16532666916589714</td>
<td>-0.24908655738050606</td>
<td>0.2429026558860896</td>
<td align="right">3</td>
<td align="right">1</td>
</tr>
<tr>
<td>x88</td>
<td align="right">150550</td>
<td>Paragominas</td>
<td>1.5915563484056177</td>
<td>1.1154489689670224</td>
<td>1.4720082854396632</td>
<td>-1.4705452438880622</td>
<td align="right">0</td>
<td align="right">40</td>
</tr>
<tr>
<td>x89</td>
<td align="right">150553</td>
<td>Parauapebas</td>
<td>1.852048032298861</td>
<td>2.295183639780423</td>
<td>2.1183124617732294</td>
<td>-0.6508373064444771</td>
<td align="right">0</td>
<td align="right">68</td>
</tr>
<tr>
<td>x90</td>
<td align="right">150555</td>
<td>Pau D&#39;Arco</td>
<td>-1.3899782178749143</td>
<td>-0.1564533651981872</td>
<td>0.6892921378923007</td>
<td>-1.0517172529984826</td>
<td align="right">3</td>
<td align="right">0</td>
</tr>
<tr>
<td>x91</td>
<td align="right">150560</td>
<td>Peixe-Boi</td>
<td>-0.6886512391544619</td>
<td>-0.037988351230282213</td>
<td>-1.9557812086503241</td>
<td>0.6045853465832371</td>
<td align="right">3</td>
<td align="right">3</td>
</tr>
<tr>
<td>x92</td>
<td align="right">150563</td>
<td>Piçarra</td>
<td>0.009898072981534015</td>
<td>-0.3219708901819884</td>
<td>0.7012566470075954</td>
<td>0.2429026558860896</td>
<td align="right">2</td>
<td align="right">3</td>
</tr>
<tr>
<td>x93</td>
<td align="right">150565</td>
<td>Placas</td>
<td>-1.3899782178749143</td>
<td>-0.48699393885129033</td>
<td>-0.6042098766405811</td>
<td>1.4705452438880622</td>
<td align="right">3</td>
<td align="right">0</td>
</tr>
<tr>
<td>x94</td>
<td align="right">150570</td>
<td>Ponta de Pedras</td>
<td>-0.6886512391544619</td>
<td>-0.3487556955170447</td>
<td>-1.4300371593192172</td>
<td>0.6045853465832371</td>
<td align="right">3</td>
<td align="right">9</td>
</tr>
<tr>
<td>x95</td>
<td align="right">150580</td>
<td>Portel</td>
<td>1.6550352213773933</td>
<td>-1.757249724026964</td>
<td>0.2940796832518405</td>
<td>-1.0517172529984826</td>
<td align="right">1</td>
<td align="right">13</td>
</tr>
<tr>
<td>x96</td>
<td align="right">150590</td>
<td>Porto de Moz</td>
<td>0.3374821867256964</td>
<td>-1.3996566480498192</td>
<td>-0.8281728397324787</td>
<td>-0.20396117575131423</td>
<td align="right">3</td>
<td align="right">3</td>
</tr>
<tr>
<td>x97</td>
<td align="right">150600</td>
<td>Prainha</td>
<td>0.009898072981534015</td>
<td>-1.015517613293485</td>
<td>-0.14151240468137982</td>
<td>0.967421566101701</td>
<td align="right">3</td>
<td align="right">1</td>
</tr>
<tr>
<td>x98</td>
<td align="right">150610</td>
<td>Primavera</td>
<td>0.3374821867256964</td>
<td>-0.11418529432142824</td>
<td>1.0752957415752602</td>
<td>0.6045853465832371</td>
<td align="right">2</td>
<td align="right">0</td>
</tr>
<tr>
<td>x99</td>
<td align="right">150611</td>
<td>Quatipuru</td>
<td>0.3374821867256964</td>
<td>-0.7728816409849758</td>
<td>-1.1735113177725685</td>
<td>0.967421566101701</td>
<td align="right">3</td>
<td align="right">4</td>
</tr>
<tr>
<td>x100</td>
<td align="right">150613</td>
<td>Redenção</td>
<td>1.395418154614277</td>
<td>1.6157206933784676</td>
<td>1.0844833467426014</td>
<td>-1.0517172529984826</td>
<td align="right">0</td>
<td align="right">25</td>
</tr>
<tr>
<td>x101</td>
<td align="right">150616</td>
<td>Rio Maria</td>
<td>0.009898072981534015</td>
<td>0.986162162276945</td>
<td>1.4051059678192326</td>
<td>0.967421566101701</td>
<td align="right">1</td>
<td align="right">14</td>
</tr>
<tr>
<td>x102</td>
<td align="right">150618</td>
<td>Rondon do Pará</td>
<td>-0.6886512391544619</td>
<td>0.501297710767729</td>
<td>-0.08787932462194899</td>
<td>-2.166106752892329</td>
<td align="right">3</td>
<td align="right">11</td>
</tr>
<tr>
<td>x103</td>
<td align="right">150619</td>
<td>Rurópolis</td>
<td>-1.3899782178749143</td>
<td>-0.5744599931693578</td>
<td>-1.1028130962498484</td>
<td>0.6045853465832371</td>
<td align="right">3</td>
<td align="right">1</td>
</tr>
<tr>
<td>x104</td>
<td align="right">150620</td>
<td>Salinópolis</td>
<td>0.3374821867256964</td>
<td>1.1701182500084333</td>
<td>0.33349592989766985</td>
<td>0.2429026558860896</td>
<td align="right">1</td>
<td align="right">20</td>
</tr>
<tr>
<td>x105</td>
<td align="right">150630</td>
<td>Salvaterra</td>
<td>-0.6886512391544619</td>
<td>0.5936783401487544</td>
<td>-0.9581713026714971</td>
<td>0.2429026558860896</td>
<td align="right">3</td>
<td align="right">0</td>
</tr>
<tr>
<td>x106</td>
<td align="right">150635</td>
<td>Santa Bárbara do Pará</td>
<td>-0.6886512391544619</td>
<td>0.8610402050730338</td>
<td>-0.5106975983459667</td>
<td>1.4705452438880622</td>
<td align="right">2</td>
<td align="right">7</td>
</tr>
<tr>
<td>x107</td>
<td align="right">150640</td>
<td>Santa Cruz do Arari</td>
<td>0.009898072981534015</td>
<td>-0.4509651702263182</td>
<td>-1.477263231124275</td>
<td>0.967421566101701</td>
<td align="right">3</td>
<td align="right">2</td>
</tr>
<tr>
<td>x108</td>
<td align="right">150650</td>
<td>Santa Izabel do Pará</td>
<td>-1.3899782178749143</td>
<td>1.2758170414017853</td>
<td>0.14178662551253723</td>
<td>-0.20396117575131423</td>
<td align="right">2</td>
<td align="right">14</td>
</tr>
<tr>
<td>x109</td>
<td align="right">150655</td>
<td>Santa Luzia do Pará</td>
<td>1.2424787871632754</td>
<td>-0.6985257103450601</td>
<td>-0.7410251430855164</td>
<td>-0.20396117575131423</td>
<td align="right">2</td>
<td align="right">1</td>
</tr>
<tr>
<td>x110</td>
<td align="right">150658</td>
<td>Santa Maria das Barreiras</td>
<td>0.7049775102792363</td>
<td>-0.7585059570978735</td>
<td>1.144904041793299</td>
<td>0.6045853465832371</td>
<td align="right">1</td>
<td align="right">0</td>
</tr>
<tr>
<td>x111</td>
<td align="right">150660</td>
<td>Santa Maria do Pará</td>
<td>0.009898072981534015</td>
<td>0.41785061995716205</td>
<td>0.2280471339147734</td>
<td>0.967421566101701</td>
<td align="right">2</td>
<td align="right">8</td>
</tr>
<tr>
<td>x112</td>
<td align="right">150670</td>
<td>Santana do Araguaia</td>
<td>0.009898072981534015</td>
<td>0.501297710767729</td>
<td>0.4600046285639994</td>
<td>-0.20396117575131423</td>
<td align="right">2</td>
<td align="right">3</td>
</tr>
<tr>
<td>x113</td>
<td align="right">150680</td>
<td>Santarém</td>
<td>1.395418154614277</td>
<td>2.0165329237566016</td>
<td>0.7305517719212055</td>
<td>-2.166106752892329</td>
<td align="right">0</td>
<td align="right">144</td>
</tr>
<tr>
<td>x114</td>
<td align="right">150690</td>
<td>Santarém Novo</td>
<td>0.3374821867256964</td>
<td>0.08837646690321847</td>
<td>-1.691013262039149</td>
<td>5.19933758270342</td>
<td align="right">1</td>
<td align="right">0</td>
</tr>
<tr>
<td>x115</td>
<td align="right">150700</td>
<td>Santo Antônio do Tauá</td>
<td>-1.3899782178749143</td>
<td>0.9041176612839913</td>
<td>0.2663792222588275</td>
<td>0.6045853465832371</td>
<td align="right">2</td>
<td align="right">7</td>
</tr>
<tr>
<td>x116</td>
<td align="right">150710</td>
<td>São Caetano de Odivelas</td>
<td>0.3374821867256964</td>
<td>0.0568313523201203</td>
<td>-0.731146234646388</td>
<td>-0.20396117575131423</td>
<td align="right">3</td>
<td align="right">5</td>
</tr>
<tr>
<td>x117</td>
<td align="right">150715</td>
<td>São Domingos do Araguaia</td>
<td>-1.3899782178749143</td>
<td>0.2954151418352379</td>
<td>0.08866719272172413</td>
<td>-1.0517172529984826</td>
<td align="right">3</td>
<td align="right">3</td>
</tr>
<tr>
<td>x118</td>
<td align="right">150720</td>
<td>São Domingos do Capim</td>
<td>0.009898072981534015</td>
<td>-0.9072355384788398</td>
<td>0.000749818370094455</td>
<td>-0.6508373064444771</td>
<td align="right">3</td>
<td align="right">4</td>
</tr>
<tr>
<td>x119</td>
<td align="right">150730</td>
<td>São Félix do Xingu</td>
<td>0.3374821867256964</td>
<td>0.2954151418352379</td>
<td>0.16749633567446395</td>
<td>-1.7460165226992128</td>
<td align="right">2</td>
<td align="right">9</td>
</tr>
<tr>
<td>x120</td>
<td align="right">150740</td>
<td>São Francisco do Pará</td>
<td>-1.3899782178749143</td>
<td>0.5936783401487544</td>
<td>0.5751732918532133</td>
<td>1.4705452438880622</td>
<td align="right">2</td>
<td align="right">2</td>
</tr>
<tr>
<td>x121</td>
<td align="right">150745</td>
<td>São Geraldo do Araguaia</td>
<td>-1.3899782178749143</td>
<td>0.348755695517045</td>
<td>0.981626940415326</td>
<td>-1.4705452438880622</td>
<td align="right">2</td>
<td align="right">1</td>
</tr>
<tr>
<td>x122</td>
<td align="right">150746</td>
<td>São João da Ponta</td>
<td>0.009898072981534015</td>
<td>0.02488550311706342</td>
<td>-0.9873409327877699</td>
<td>0.967421566101701</td>
<td align="right">3</td>
<td align="right">0</td>
</tr>
<tr>
<td>x123</td>
<td align="right">150747</td>
<td>São João de Pirabas</td>
<td>-0.6886512391544619</td>
<td>-0.8517259806982667</td>
<td>-1.2053072394099615</td>
<td>0.6045853465832371</td>
<td align="right">3</td>
<td align="right">7</td>
</tr>
<tr>
<td>x124</td>
<td align="right">150750</td>
<td>São João do Araguaia</td>
<td>-0.6886512391544619</td>
<td>-0.517723552817668</td>
<td>-0.24069449211000038</td>
<td>-1.0517172529984826</td>
<td align="right">3</td>
<td align="right">3</td>
</tr>
<tr>
<td>x125</td>
<td align="right">150760</td>
<td>São Miguel do Guamá</td>
<td>0.009898072981534015</td>
<td>0.21690442598171078</td>
<td>-0.02378627629264218</td>
<td>-0.6508373064444771</td>
<td align="right">2</td>
<td align="right">17</td>
</tr>
<tr>
<td>x126</td>
<td align="right">150770</td>
<td>São Sebastião da Boa Vista</td>
<td>-1.3899782178749143</td>
<td>-0.4357699298335434</td>
<td>-0.9231628535966067</td>
<td>1.4705452438880622</td>
<td align="right">3</td>
<td align="right">3</td>
</tr>
<tr>
<td>x127</td>
<td align="right">150775</td>
<td>Sapucaia</td>
<td>0.009898072981534015</td>
<td>0.1960858250215825</td>
<td>0.7593280463943072</td>
<td>-0.20396117575131423</td>
<td align="right">2</td>
<td align="right">0</td>
</tr>
<tr>
<td>x128</td>
<td align="right">150780</td>
<td>Senador José Porfírio</td>
<td>-0.6886512391544619</td>
<td>-1.1708311189567913</td>
<td>0.42159758681984205</td>
<td>0.2429026558860896</td>
<td align="right">3</td>
<td align="right">2</td>
</tr>
<tr>
<td>x129</td>
<td align="right">150790</td>
<td>Soure</td>
<td>1.4813016392052942</td>
<td>0.6985257103450605</td>
<td>-0.8676971785036826</td>
<td>-0.20396117575131423</td>
<td align="right">1</td>
<td align="right">2</td>
</tr>
<tr>
<td>x130</td>
<td align="right">150795</td>
<td>Tailândia</td>
<td>0.8938074348664315</td>
<td>0.11418529432142852</td>
<td>-0.42982496358014394</td>
<td>-0.20396117575131423</td>
<td align="right">2</td>
<td align="right">11</td>
</tr>
<tr>
<td>x131</td>
<td align="right">150796</td>
<td>Terra Alta</td>
<td>-1.3899782178749143</td>
<td>0.5504821475527473</td>
<td>-2.4110926139292808</td>
<td>-0.20396117575131423</td>
<td align="right">3</td>
<td align="right">3</td>
</tr>
<tr>
<td>x132</td>
<td align="right">150797</td>
<td>Terra Santa</td>
<td>-1.3899782178749143</td>
<td>0.9394728248202913</td>
<td>1.2781667821545464</td>
<td>0.2429026558860896</td>
<td align="right">1</td>
<td align="right">4</td>
</tr>
<tr>
<td>x133</td>
<td align="right">150800</td>
<td>Tomé-Açu</td>
<td>0.009898072981534015</td>
<td>0.07066802212729008</td>
<td>0.12975707039955364</td>
<td>-0.6508373064444771</td>
<td align="right">2</td>
<td align="right">10</td>
</tr>
<tr>
<td>x134</td>
<td align="right">150803</td>
<td>Tracuateua</td>
<td>0.009898072981534015</td>
<td>-0.9202578755274337</td>
<td>-1.075547853739558</td>
<td>0.967421566101701</td>
<td align="right">3</td>
<td align="right">1</td>
</tr>
<tr>
<td>x135</td>
<td align="right">150805</td>
<td>Trairão</td>
<td>0.009898072981534015</td>
<td>-0.3487556955170447</td>
<td>0.5654533233509392</td>
<td>1.4705452438880622</td>
<td align="right">2</td>
<td align="right">1</td>
</tr>
<tr>
<td>x136</td>
<td align="right">150808</td>
<td>Tucumã</td>
<td>0.009898072981534015</td>
<td>1.2758170414017853</td>
<td>0.959303068153797</td>
<td>0.2429026558860896</td>
<td align="right">1</td>
<td align="right">12</td>
</tr>
<tr>
<td>x137</td>
<td align="right">150810</td>
<td>Tucuruí</td>
<td>1.9742932230425354</td>
<td>1.4713798467412988</td>
<td>1.7933110331709872</td>
<td>-1.0517172529984826</td>
<td align="right">0</td>
<td align="right">52</td>
</tr>
<tr>
<td>x138</td>
<td align="right">150812</td>
<td>Ulianópolis</td>
<td>-1.3899782178749143</td>
<td>0.5399175656801211</td>
<td>1.3343670089427027</td>
<td>-0.20396117575131423</td>
<td align="right">2</td>
<td align="right">3</td>
</tr>
<tr>
<td>x139</td>
<td align="right">150815</td>
<td>Uruará</td>
<td>-0.6886512391544619</td>
<td>0.16532666916589714</td>
<td>0.37361015246640894</td>
<td>-0.20396117575131423</td>
<td align="right">2</td>
<td align="right">2</td>
</tr>
<tr>
<td>x140</td>
<td align="right">150820</td>
<td>Vigia</td>
<td>-1.3899782178749143</td>
<td>0.7304027280141283</td>
<td>-1.3505262778717937</td>
<td>0.6045853465832371</td>
<td align="right">3</td>
<td align="right">10</td>
</tr>
<tr>
<td>x141</td>
<td align="right">150830</td>
<td>Viseu</td>
<td>-0.6886512391544619</td>
<td>-1.1202053547494892</td>
<td>-0.779781986131154</td>
<td>0.2429026558860896</td>
<td align="right">3</td>
<td align="right">4</td>
</tr>
<tr>
<td>x142</td>
<td align="right">150835</td>
<td>Vitória do Xingu</td>
<td>1.6550352213773933</td>
<td>0.37962290989397623</td>
<td>2.862648443481207</td>
<td>-0.20396117575131423</td>
<td align="right">0</td>
<td align="right">6</td>
</tr>
<tr>
<td>x143</td>
<td align="right">150840</td>
<td>Xinguara</td>
<td>0.009898072981534015</td>
<td>1.1418385701455165</td>
<td>1.5514273806932608</td>
<td>-0.6508373064444771</td>
<td align="right">1</td>
<td align="right">13</td>
</tr>
</tbody></table>

## Autores

We thank you all for your valuable contributions to this project:

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="collaborators/joao.jpg" width="100px;" alt="joao"><br>
        <sub>
          <b>João L. De Souza</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="collaborators/saulo.jpg" width="100px;alt="Sulo"><br>
        <sub>
          <b>Saulo William</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="collaborators/alana.jpg" width="100px;" alt="Alana"><br>
        <sub>
          <b>Alana Miranda</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="collaborators/fernando.jpg" width="100px;alt="Seruffo"><br>
        <sub>
          <b>Fernando Costa</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="collaborators/seruffo.jpg" width="100px;alt="Seruffo"><br>
        <sub>
          <b>Marcos Seruffo</b>
        </sub>
      </a>
    </td>
    
  </tr>
</table>
