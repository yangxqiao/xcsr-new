---
title: Leaderboard
layout: page
show_sidebar: false
hide_footer: true
toc: true
---

<style>
.avg{
    font-weight: 800;
    color: green;
}

</style>

<style>
/* Tooltip container */
.tooltip {
}

/* Tooltip text */
.tooltip .tooltiptext {
  visibility: hidden;
  width: 200px;
  background-color: black;
  color: #fff;
  text-align: center;
  padding: 5px 0;
  border-radius: 6px;
 
  /* Position the tooltip text - see examples below! */
  position: absolute;
  z-index: 1;
}

/* Show the tooltip text when you mouse over the tooltip container */
.tooltip:hover .tooltiptext {
  visibility: visible;
}
</style>


<!-- ![Mickey](images/all_results.png){: style="text-align:center; display:block; margin-left: auto; margin-right: auto;" width="100%"} -->


## X-CODAH Results
<table id='XCODAH'>
<thead>
<tr>
    <th class='model'>Model</th>
    <th>Participant</th>
    <th>Date</th>
    <th class="avg"><em>AVG</em></th>
    <th>en</th>
    <th>de</th>
    <th>it</th>
    <th>es</th>
    <th>fr</th>
    <th>nl</th>
    <th>ru</th>
    <th>vi</th>
    <th>zh</th>
    <th>hi</th>
    <th>pl</th>
    <th>ar</th>
    <th>ja</th>
    <th>pt</th>
    <th>sw</th>
    <th>ur</th>
</tr>
</thead>
<tbody>
<!-- <tr>
    <td>MCP + KG</td>
    <td class="tooltip"><a>Anonymous</a> <span class="tooltiptext"><br>2021-09-20</span> </td>
    <td>09/21'</td>
    <td class="avg">63.7</td>
    <td>68.9</td>
    <td>66.4</td>
    <td>63.7</td>
    <td>66.5</td>
    <td>66.6</td>
    <td>64.6</td>
    <td>64.0</td>
    <td>66.9</td>
    <td>65.4</td>
    <td>61.9</td>
    <td>64.1</td>
    <td>62.1</td>
    <td>60.2</td>
    <td>66.2</td>
    <td>55.5</td>
    <td>57.0</td>
</tr> -->
<tr>
    <td><a href="https://arxiv.org/abs/2110.08462" target="_blank">TRT</a></td>
    <td class="tooltip"><a href="https://arxiv.org/abs/2110.08462" target="_blank">Microsoft Cognitive Services Research </a><span class="tooltiptext">yuwfan@microsoft.com<br>2021-10-15</span> </td>
    <td>10/21'</td>
    <td class="avg">61.9</td>
    <td>69.1</td>
    <td>65.3</td>
    <td>62.5</td>
    <td>64.4</td>
    <td>64.3</td>
    <td>64.5</td>
    <td>61.8</td>
    <td>64.6</td>
    <td>63.3</td>
    <td>57.1</td>
    <td>62.7</td>
    <td>57.6</td>
    <td>61.6</td>
    <td>64.3</td>
    <td>52.5</td>
    <td>55.1</td>
</tr>
<tr>
    <td>MCP(RL)</td>
    <td class="tooltip"><a>USC-INK</a> <span class="tooltiptext">yuchen.lin@usc.edu <br> 2021-06-01</span> </td>
    <td>06/21'</td>
    <td class="avg">58.3</td>
    <td>69.9</td>
    <td>60.7</td>
    <td>61.9</td>
    <td>60.7</td>
    <td>61.4</td>
    <td>60.7</td>
    <td>58.6</td>
    <td>62.3</td>
    <td>61.9</td>
    <td>53.7</td>
    <td>59.0</td>
    <td>54.1</td>
    <td>54.7</td>
    <td>60.8</td>
    <td>44.6</td>
    <td>48.0</td>
</tr>
<tr>
    <td>XLMR-L</td>
    <td class="tooltip"><a>USC-INK</a> <span class="tooltiptext">yuchen.lin@usc.edu <br> 2021-06-01</span> </td>
    <td>06/21'</td>
    <td class="avg">56.0</td>
    <td>66.4</td>
    <td>59.6</td>
    <td>59.9</td>
    <td>60.9</td>
    <td>60.1</td>
    <td>59.3</td>
    <td>56.3</td>
    <td>57.4</td>
    <td>57.3</td>
    <td>49.1</td>
    <td>57.5</td>
    <td>51.2</td>
    <td>53.8</td>
    <td>58.2</td>
    <td>42.2</td>
    <td>46.6</td>
</tr>
<tr>
    <td>MCP(RB)</td>
    <td class="tooltip"><a>USC-INK</a> <span class="tooltiptext">yuchen.lin@usc.edu <br> 2021-06-01</span> </td>
    <td>06/21'</td>
    <td class="avg">43.6</td>
    <td>52.2</td>
    <td>47.6</td>
    <td>46.2</td>
    <td>44.4</td>
    <td>48.1</td>
    <td>44.8</td>
    <td>42.9</td>
    <td>43.2</td>
    <td>45.7</td>
    <td>37.8</td>
    <td>41.8</td>
    <td>41.8</td>
    <td>42.9</td>
    <td>44.7</td>
    <td>37.2</td>
    <td>36.4</td>
</tr>
<tr>
    <td>XLMR-B</td>
    <td class="tooltip"><a>USC-INK</a> <span class="tooltiptext">yuchen.lin@usc.edu <br> 2021-06-01</span> </td>
    <td>06/21'</td>
    <td class="avg">42.4</td>
    <td>50.1</td>
    <td>45.8</td>
    <td>44.4</td>
    <td>44.2</td>
    <td>45.2</td>
    <td>42.0</td>
    <td>44.1</td>
    <td>43.2</td>
    <td>44.6</td>
    <td>38.1</td>
    <td>41.9</td>
    <td>37.8</td>
    <td>42.0</td>
    <td>44.1</td>
    <td>35.6</td>
    <td>34.6</td>
</tr>
<tr>
    <td>mBERT</td>
    <td class="tooltip"><a>USC-INK</a> <span class="tooltiptext">yuchen.lin@usc.edu <br> 2021-06-01</span> </td>
    <td>06/21'</td>
    <td class="avg">33.2</td>
    <td>42.9</td>
    <td>33.1</td>
    <td>33.5</td>
    <td>33.8</td>
    <td>35.2</td>
    <td>33.7</td>
    <td>31.9</td>
    <td>22.8</td>
    <td>38.0</td>
    <td>26.5</td>
    <td>31.0</td>
    <td>34.8</td>
    <td>34.0</td>
    <td>37.2</td>
    <td>30.8</td>
    <td>31.5</td>
</tr>
<tr>
    <td>XLM-100</td>
    <td class="tooltip"><a>USC-INK</a> <span class="tooltiptext">yuchen.lin@usc.edu <br> 2021-06-01</span> </td>
    <td>06/21'</td>
    <td class="avg">30.4</td>
    <td>42.7</td>
    <td>31.5</td>
    <td>32.2</td>
    <td>30.7</td>
    <td>34.9</td>
    <td>32.6</td>
    <td>30.9</td>
    <td>24.7</td>
    <td>31.4</td>
    <td>26.8</td>
    <td>27.0</td>
    <td>30.0</td>
    <td>27.4</td>
    <td>33.2</td>
    <td>25.3</td>
    <td>24.9</td>
</tr>
</tbody>
</table>



## X-CSQA Results

<table id='XCSQA'>
<thead>
<tr>
    <th class='model'>Model</th>
    <th>Participant</th>
    <th>Date</th>
    <th class="avg"><em>AVG</em></th>
    <th>en</th>
    <th>de</th>
    <th>it</th>
    <th>es</th>
    <th>fr</th>
    <th>nl</th>
    <th>ru</th>
    <th>vi</th>
    <th>zh</th>
    <th>hi</th>
    <th>pl</th>
    <th>ar</th>
    <th>ja</th>
    <th>pt</th>
    <th>sw</th>
    <th>ur</th>
</tr>
</thead>
<tbody>
<!-- <tr>
    <td>MCP + KG</td>
    <td class="tooltip"><a>Anonymous</a> <span class="tooltiptext"><br>2021-09-20</span> </td>
    <td>09/21'</td>
    <td class="avg">59.8</td>
    <td>68.2</td>
    <td>62.1</td>
    <td>61.6</td>
    <td>64.4</td>
    <td>64.6</td>
    <td>61.9</td>
    <td>58.2</td>
    <td>60.7</td>
    <td>58.7</td>
    <td>55.5</td>
    <td>60.8</td>
    <td>56.4</td>
    <td>56.2</td>
    <td>63.2</td>
    <td>51.2</td>
    <td>53.3</td>
</tr> -->
<tr>
    <td><a href="https://arxiv.org/abs/2110.08462" target="_blank">TRT</a></td>
    <td class="tooltip"><a  href="https://arxiv.org/abs/2110.08462" target="_blank">Microsoft Cognitive Services Research </a> <span class="tooltiptext">yuwfan@microsoft.com<br>2021-10-15</span> </td>
        <td>10/21'</td>
    <td class="avg">59.8</td>
    <td>71.0</td>
    <td>61.2</td>
    <td>63.0</td>
    <td>65.1</td>
    <td>65.1</td>
    <td>62.8</td>
    <td>57.8</td>
    <td>58.9</td>
    <td>56.3</td>
    <td>56.1</td>
    <td>59.4</td>
    <td>56.2</td>
    <td>54.7</td>
    <td>64.6</td>
    <td>51.0</td>
    <td>53.9</td>
</tr>
<tr>
    <td>MCP(RL)</td>
    <td class="tooltip"><a>USC-INK</a> <span class="tooltiptext">yuchen.lin@usc.edu <br> 2021-06-01</span> </td>
    <td>06/21'</td>
    <td class="avg">56.5</td>
    <td>69.5</td>
    <td>59.3</td>
    <td>60.3</td>
    <td>61.4</td>
    <td>60.0</td>
    <td>61.1</td>
    <td>57.5</td>
    <td>55.7</td>
    <td>56.7</td>
    <td>51.3</td>
    <td>56.1</td>
    <td>52.3</td>
    <td>50.2</td>
    <td>60.7</td>
    <td>43.3</td>
    <td>48.8</td>
</tr>
<tr>
    <td>XLMR-L</td>
    <td class="tooltip"><a>USC-INK</a> <span class="tooltiptext">yuchen.lin@usc.edu <br> 2021-06-01</span> </td>
    <td>06/21'</td>
    <td class="avg">53.8</td>
    <td>66.7</td>
    <td>56.1</td>
    <td>58.2</td>
    <td>59.5</td>
    <td>60.3</td>
    <td>56.8</td>
    <td>52.1</td>
    <td>51.4</td>
    <td>52.7</td>
    <td>48.7</td>
    <td>53.9</td>
    <td>48.4</td>
    <td>50.0</td>
    <td>59.9</td>
    <td>41.6</td>
    <td>45.2</td>
</tr>
<tr>
    <td>MCP(RB)</td>
    <td class="tooltip"><a>USC-INK</a> <span class="tooltiptext">yuchen.lin@usc.edu <br> 2021-06-01</span> </td>
    <td>06/21'</td>
    <td class="avg">41.9</td>
    <td>52.1</td>
    <td>46.2</td>
    <td>45.6</td>
    <td>44.3</td>
    <td>44.7</td>
    <td>45.3</td>
    <td>42.8</td>
    <td>45.3</td>
    <td>44.3</td>
    <td>36.8</td>
    <td>41.4</td>
    <td>36.8</td>
    <td>37.5</td>
    <td>44.9</td>
    <td>28.1</td>
    <td>33.4</td>
</tr>
<tr>
    <td>XLMR-B</td>
    <td class="tooltip"><a>USC-INK</a> <span class="tooltiptext">yuchen.lin@usc.edu <br> 2021-06-01</span> </td>
    <td>06/21'</td>
    <td class="avg">40.6</td>
    <td>51.5</td>
    <td>44.1</td>
    <td>42.1</td>
    <td>44.8</td>
    <td>44.0</td>
    <td>43.3</td>
    <td>39.5</td>
    <td>42.6</td>
    <td>40.6</td>
    <td>34.6</td>
    <td>40.2</td>
    <td>38.4</td>
    <td>37.5</td>
    <td>43.4</td>
    <td>29.6</td>
    <td>33.0</td>
</tr>
<tr>
    <td>mBERT</td>
    <td class="tooltip"><a>USC-INK</a> <span class="tooltiptext">yuchen.lin@usc.edu <br> 2021-06-01</span> </td>
    <td>06/21'</td>
    <td class="avg">30.4</td>
    <td>38.8</td>
    <td>29.6</td>
    <td>36.4</td>
    <td>35.3</td>
    <td>33.8</td>
    <td>32.6</td>
    <td>32.7</td>
    <td>22.2</td>
    <td>37.8</td>
    <td>21.1</td>
    <td>27.2</td>
    <td>27.7</td>
    <td>31.4</td>
    <td>34.1</td>
    <td>21.8</td>
    <td>23.7</td>
</tr>
<tr>
    <td>XLM-100</td>
    <td class="tooltip"><a>USC-INK</a> <span class="tooltiptext">yuchen.lin@usc.edu <br> 2021-06-01</span> </td>
    <td>06/21'</td>
    <td class="avg">26.7</td>
    <td>34.3</td>
    <td>26.7</td>
    <td>28.5</td>
    <td>29.3</td>
    <td>28.3</td>
    <td>27.2</td>
    <td>29.9</td>
    <td>21.1</td>
    <td>28.6</td>
    <td>22.1</td>
    <td>26.6</td>
    <td>26.3</td>
    <td>25.1</td>
    <td>30.9</td>
    <td>20.1</td>
    <td>21.7</td>
</tr>
</tbody>
</table>

---

[Enlarge the Tables](../full_table.html){: .btn .btn-red}

## Submission Instruction
If you have a model for solving X-CSR and would like to make a submission, you can [***create a submission***](https://xcsr-leaderboard.herokuapp.com/) and evaluate your model for the X-CSR dataset. 


### Submission Format
Please submit a ***.json*** file follows the format below
```json
{
    "en": {"be11daf79ced159b": "A", "8abe4f22cf8b2839": "B",..., "7a7bb4af46f9e09c": "C"},
    "fr": {"be11daf79ced159b": "A", "8abe4f22cf8b2839": "B",..., "16b2a162f9656b79": "C"},
    "it": {"be11daf79ced159b": "A", "8abe4f22cf8b2839": "B",..., "34bb7281c8e007f9": "C"},
    ...,
    "jap": {"be11daf79ced159b": "A", "8abe4f22cf8b2839": "B",..., "16b2a162f9656b79": "C"}
}
```

Your submission will be reviewed by the X-CSR team and added to the leaderboard.