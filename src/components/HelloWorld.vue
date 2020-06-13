<template>
  <div>
      <h1>黑白迭代</h1>

      <div id="">
          <div class="row">
            <div :class="['item', 'item-' + all[1] ]" data-num="1" @click="clickMe">1</div>
            <div :class="['item', 'item-' + all[2] ]" data-num="2" @click="clickMe">2</div>
            <div :class="['item', 'item-' + all[3] ]" data-num="3" @click="clickMe">3</div>
            <div :class="['item', 'item-' + all[4] ]" data-num="4" @click="clickMe">4</div>
            <div :class="['item', 'item-' + all[5] ]" data-num="5" @click="clickMe">5</div>
            <div :class="['item', 'item-' + all[6] ]" data-num="6" @click="clickMe">6</div>
            <div :class="['item', 'item-' + all[7] ]" data-num="7" @click="clickMe">7</div>
            <div :class="['item', 'item-' + all[8] ]" data-num="8" @click="clickMe">8</div>
          </div>
          <div class="row">
            <div :class="['item', 'item-' + all[9] ]" data-num="9" @click="clickMe">9</div>
            <div :class="['item', 'item-' + all[10] ]" data-num="10" @click="clickMe">10</div>
            <div :class="['item', 'item-' + all[11] ]" data-num="11" @click="clickMe">11</div>
            <div :class="['item', 'item-' + all[12] ]" data-num="12" @click="clickMe">12</div>
            <div :class="['item', 'item-' + all[13] ]" data-num="13" @click="clickMe">13</div>
            <div :class="['item', 'item-' + all[14] ]" data-num="14" @click="clickMe">14</div>
            <div :class="['item', 'item-' + all[15] ]" data-num="15" @click="clickMe">15</div>
            <div :class="['item', 'item-' + all[16] ]" data-num="16" @click="clickMe">16</div>
          </div>
          <div class="row">
            <div :class="['item', 'item-' + all[17] ]" data-num="17" @click="clickMe">17</div>
            <div :class="['item', 'item-' + all[18] ]" data-num="18" @click="clickMe">18</div>
            <div :class="['item', 'item-' + all[19] ]" data-num="19" @click="clickMe">19</div>
            <div :class="['item', 'item-' + all[20] ]" data-num="20" @click="clickMe">20</div>
            <div :class="['item', 'item-' + all[21] ]" data-num="21" @click="clickMe">21</div>
            <div :class="['item', 'item-' + all[22] ]" data-num="22" @click="clickMe">22</div>
            <div :class="['item', 'item-' + all[23] ]" data-num="23" @click="clickMe">23</div>
            <div :class="['item', 'item-' + all[24] ]" data-num="24" @click="clickMe">24</div>
          </div>
          <div class="row">
            <div :class="['item', 'item-' + all[25] ]" data-num="25" @click="clickMe">25</div>
            <div :class="['item', 'item-' + all[26] ]" data-num="26" @click="clickMe">26</div>
            <div :class="['item', 'item-' + all[27] ]" data-num="27" @click="clickMe">27</div>
            <div :class="['item', 'item-' + all[28] ]" data-num="28" @click="clickMe">28</div>
            <div :class="['item', 'item-' + all[29] ]" data-num="29" @click="clickMe">29</div>
            <div :class="['item', 'item-' + all[30] ]" data-num="30" @click="clickMe">30</div>
            <div :class="['item', 'item-' + all[31] ]" data-num="31" @click="clickMe">31</div>
            <div :class="['item', 'item-' + all[32] ]" data-num="32" @click="clickMe">32</div>
          </div>
          <div class="row">
            <div :class="['item', 'item-' + all[33] ]" data-num="33" @click="clickMe">33</div>
            <div :class="['item', 'item-' + all[34] ]" data-num="34" @click="clickMe">34</div>
            <div :class="['item', 'item-' + all[35] ]" data-num="35" @click="clickMe">35</div>
            <div :class="['item', 'item-' + all[36] ]" data-num="36" @click="clickMe">36</div>
            <div :class="['item', 'item-' + all[37] ]" data-num="37" @click="clickMe">37</div>
            <div :class="['item', 'item-' + all[38] ]" data-num="38" @click="clickMe">38</div>
            <div :class="['item', 'item-' + all[39] ]" data-num="39" @click="clickMe">39</div>
            <div :class="['item', 'item-' + all[40] ]" data-num="40" @click="clickMe">40</div>
          </div>
          <div class="row">
            <div :class="['item', 'item-' + all[41] ]" data-num="41" @click="clickMe">41</div>
            <div :class="['item', 'item-' + all[42] ]" data-num="42" @click="clickMe">42</div>
            <div :class="['item', 'item-' + all[43] ]" data-num="43" @click="clickMe">43</div>
            <div :class="['item', 'item-' + all[44] ]" data-num="44" @click="clickMe">44</div>
            <div :class="['item', 'item-' + all[45] ]" data-num="45" @click="clickMe">45</div>
            <div :class="['item', 'item-' + all[46] ]" data-num="46" @click="clickMe">46</div>
            <div :class="['item', 'item-' + all[47] ]" data-num="47" @click="clickMe">47</div>
            <div :class="['item', 'item-' + all[48] ]" data-num="48" @click="clickMe">48</div>
          </div>
          <div class="row">
            <div :class="['item', 'item-' + all[49] ]" data-num="49" @click="clickMe">49</div>
            <div :class="['item', 'item-' + all[50] ]" data-num="50" @click="clickMe">50</div>
            <div :class="['item', 'item-' + all[51] ]" data-num="51" @click="clickMe">51</div>
            <div :class="['item', 'item-' + all[52] ]" data-num="52" @click="clickMe">52</div>
            <div :class="['item', 'item-' + all[53] ]" data-num="53" @click="clickMe">53</div>
            <div :class="['item', 'item-' + all[54] ]" data-num="54" @click="clickMe">54</div>
            <div :class="['item', 'item-' + all[55] ]" data-num="55" @click="clickMe">55</div>
            <div :class="['item', 'item-' + all[56] ]" data-num="56" @click="clickMe">56</div>
          </div>
          <div class="row">
            <div :class="['item', 'item-' + all[57] ]" data-num="57" @click="clickMe">57</div>
            <div :class="['item', 'item-' + all[58] ]" data-num="58" @click="clickMe">58</div>
            <div :class="['item', 'item-' + all[59] ]" data-num="59" @click="clickMe">59</div>
            <div :class="['item', 'item-' + all[60] ]" data-num="60" @click="clickMe">60</div>
            <div :class="['item', 'item-' + all[61] ]" data-num="61" @click="clickMe">61</div>
            <div :class="['item', 'item-' + all[62] ]" data-num="62" @click="clickMe">62</div>
            <div :class="['item', 'item-' + all[63] ]" data-num="63" @click="clickMe">63</div>
            <div :class="['item', 'item-' + all[64] ]" data-num="64" @click="clickMe">64</div>
          </div>
          <div class="line"></div>
          <div class="tool">
            <button @click="build">出题</button>
            <button @click="reset">重置</button>
          </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      "rela": {
        // 第一行
        "1": [1,2,9],
        "2": [1,2,3,10],
        "3": [2,3,4,11],
        "4": [3,4,5,12],
        "5": [4,5,6,13],
        "6": [5,6,7,14],
        "7": [6,7,8,15],
        "8": [7,8,16],

        // 第二行
        "9": [1,9,10,17],
        "10": [2,9,10,11,18],
        "11": [3,10,11,12,19],
        "12": [4,11,12,13,20],
        "13": [5,12,13,14,21],
        "14": [6,13,14,15,22],
        "15": [7,14,15,16,23],
        "16": [8,15,16,24],

        // 第三行
        "17": [9,17,18,25],
        "18": [10,17,18,19,26],
        "19": [11,18,19,20,27],
        "20": [12,19,20,21,28],
        "21": [13,20,21,22,29],
        "22": [14,21,22,23,30],
        "23": [15,22,23,24,31],
        "24": [16,23,24,32],

        
        // 第四行
        "25": [17,25,26,33],
        "26": [18,25,26,27,34],
        "27": [19,26,27,28,35],
        "28": [20,27,28,29,36],
        "29": [21,28,29,30,37],
        "30": [22,29,30,31,38],
        "31": [23,30,31,32,39],
        "32": [24,31,32,40],
                
        // 第五行
        "33": [25,33,34,41],
        "34": [26,33,34,35,42],
        "35": [27,34,35,36,43],
        "36": [28,35,36,37,44],
        "37": [29,36,37,38,45],
        "38": [30,37,38,39,46],
        "39": [31,38,39,40,47],
        "40": [32,39,40,48],

        // 第六行
        "41": [33,41,42,49],
        "42": [34,41,42,43,50],
        "43": [35,42,43,44,51],
        "44": [36,43,44,45,52],
        "45": [37,44,45,46,53],
        "46": [38,45,46,47,54],
        "47": [39,46,47,48,55],
        "48": [40,47,48,56],
        
        // 第七行
        "49": [41,49,50,57],
        "50": [42,49,50,51,58],
        "51": [43,50,51,52,59],
        "52": [44,51,52,53,60],
        "53": [45,52,53,54,61],
        "54": [46,53,54,55,62],
        "55": [47,54,55,56,63],
        "56": [48,55,56,64],

                
        // 第八行
        "57": [49,57,58],
        "58": [50,57,58,59],
        "59": [51,58,59,60],
        "60": [52,59,60,61],
        "61": [53,60,61,62],
        "62": [54,61,62,63],
        "63": [55,62,63,64],
        "64": [56,63,64],
      },
      "all": {
        "1": 0,
        "2": 0,
        "3": 0,
        "4": 0,
        "5": 0,
        "6": 0,
        "7": 0,
        "8": 0,
        "9": 0,
        "10": 0,
        "11": 0,
        "12": 0,
        "13": 0,
        "14": 0,
        "15": 0,
        "16": 0,
        "17": 0,
        "18": 0,
        "19": 0,
        "20": 0,
        "21": 0,
        "22": 0,
        "23": 0,
        "24": 0,
        "25": 0,
        "26": 0,
        "27": 0,
        "28": 0,
        "29": 0,
        "30": 0,
        "31": 0,
        "32": 0,
        "33": 0,
        "34": 0,
        "35": 0,
        "36": 0,
        "37": 0,
        "38": 0,
        "39": 0,
        "40": 0,
        "41": 0,
        "42": 0,
        "43": 0,
        "44": 0,
        "45": 0,
        "46": 0,
        "47": 0,
        "48": 0,
        "49": 0,
        "50": 0,
        "51": 0,
        "52": 0,
        "53": 0,
        "54": 0,
        "55": 0,
        "56": 0,
        "57": 0,
        "58": 0,
        "59": 0,
        "60": 0,
        "61": 0,
        "62": 0,
        "63": 0,
        "64": 0,
      },
      steps:[]
    }
  },
  methods: {
    clickMe: function (e) {
      let num = e.target.dataset.num
      this.click(num)

    },
    click: function (num) {
      // 记录步骤
      this.steps.push(num)

      for (const i of this.rela[num]) {
        if (this.all[i] == 1) {
          this.all[i] = 0
        } else {
          this.all[i] = 1
        }
      }
    },

    getRandoms: function (length) {
      let randoms = []
      for (let i = 0; i < length; i++) {
        let rand = Math.floor( Math.random() * 64);
        if (rand == 0) {
          continue
        }
        randoms.push(rand)
      }

      return randoms
    },

    build: function () {
      // 重置
      this.reset()
      let steps = this.getRandoms(10)
      console.log(steps)
      for (const i of steps) {
        this.click(i)
        this.steps.push(i)
      }
    },

    reset: function () {
      for (const i in this.all) {
        this.all[i] = 0
        this.steps = []
      }
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.item{
  width: 2.5rem;
  height: 2.5rem;
  line-height: 2.5rem;
  text-align: center;
  display: inline-block;
}

.item-0 {
  background: #fff;
  color: #000;
}
.item-1 {
  background: #000;
  color: #fff;
}
.line {
  margin-top: 30px;
  height: 1px solid #000;
  border-top: 1px solid #ddd;
}
button {
  margin: 20px 10px;
  padding: 10px 30px;
  border-radius: 5px;
  border:none;
}
</style>
