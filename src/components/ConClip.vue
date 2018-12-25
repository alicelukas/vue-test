<template>
  <div class="Clip">
    <h2>최근 1년간 트게더 클립 탑 20</h2>
    <ul class="clip" id="clip-list">
      <!-- <li><p>▼▼1위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=DeterminedPreciousMelonBlargNaut&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼2위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=YawningTransparentYakinikuHumbleLife&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼3위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=FunnyTenderLadiesFailFish&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼4위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=CleverYummyRamenAMPEnergyCherry&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼5위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=SpotlessRudeBottleLitFam&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼6위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=CarelessObliviousCucumberDerp&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼7위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=OnerousCautiousDogeOSkomodo&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼8위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=DifferentMistyMangetoutDeIlluminati&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼9위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=ThirstyVivaciousGoldfishKappaRoss&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼10위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=OriginalFriendlyDumplingsPeoplesChamp&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼11위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=PunchyEmpathicBibimbapHassanChop&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼12위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=ArborealDeadCaribouMau5&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼13위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=TameAdventurousReubenKappaWealth&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼14위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=RealRelievedRadishNerfRedBlaster&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼15위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=GrossPeacefulJamKAPOW&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼16위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=BlatantTrappedKoalaHumbleLife&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼17위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=ProtectiveSmokyAardvarkKappa&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼18위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=GloriousAbstruseClintDogFace&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼19위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=FantasticAmazingMagePRChase&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>
      <li><p>▼▼20위▼▼</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip=RepletePlayfulParrotHeyGirl&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li> -->
      <li v-if="showNext" @click="clickNext" id="show-next">더 보기</li>
      <!-- <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li> -->
    </ul>
    
    <!-- <iframe src="https://www.youtube.com/channel/UCom6YhUY62jM52nIMjf5_dw/featured" onload="iframeLoad(this.document.body.innerHTML)"></iframe> -->
    <!-- <iframe src="https://www.w3schools.com"></iframe> -->
    <!-- <iframe width="560" height="315" src="https://www.youtube.com/channel/UCom6YhUY62jM52nIMjf5_dw/featured" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
    <!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/kUMo8mxN04w" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      showNext: true,

      text: [
        {'p-text': '▼▼1위▼▼', 'clip-src': 'DeterminedPreciousMelonBlargNaut'},
        {'p-text': '▼▼2위▼▼', 'clip-src': 'YawningTransparentYakinikuHumbleLife'},
        {'p-text': '▼▼3위▼▼', 'clip-src': 'FunnyTenderLadiesFailFish'},
        {'p-text': '▼▼4위▼▼', 'clip-src': 'CleverYummyRamenAMPEnergyCherry'},
        {'p-text': '▼▼5위▼▼', 'clip-src': 'SpotlessRudeBottleLitFam'},
        {'p-text': '▼▼6위▼▼', 'clip-src': 'CarelessObliviousCucumberDerp'},
        {'p-text': '▼▼7위▼▼', 'clip-src': 'OnerousCautiousDogeOSkomodo'},
        {'p-text': '▼▼8위▼▼', 'clip-src': 'DifferentMistyMangetoutDeIlluminati'},
        {'p-text': '▼▼9위▼▼', 'clip-src': 'ThirstyVivaciousGoldfishKappaRoss'},
        {'p-text': '▼▼10위▼▼',  'clip-src': 'OriginalFriendlyDumplingsPeoplesChamp'},
        {'p-text': '▼▼11위▼▼',  'clip-src': 'PunchyEmpathicBibimbapHassanChop'},
        {'p-text': '▼▼12위▼▼',  'clip-src': 'ArborealDeadCaribouMau5'},
        {'p-text': '▼▼13위▼▼',  'clip-src': 'TameAdventurousReubenKappaWealth'},
        {'p-text': '▼▼14위▼▼',  'clip-src': 'RealRelievedRadishNerfRedBlaster'},
        {'p-text': '▼▼15위▼▼',  'clip-src': 'GrossPeacefulJamKAPOW'},
        {'p-text': '▼▼16위▼▼',  'clip-src': 'BlatantTrappedKoalaHumbleLife'},
        {'p-text': '▼▼17위▼▼',  'clip-src': 'ProtectiveSmokyAardvarkKappa'},
        {'p-text': '▼▼18위▼▼',  'clip-src': 'GloriousAbstruseClintDogFace'},
        {'p-text': '▼▼19위▼▼',  'clip-src': 'FantasticAmazingMagePRChase'},
        {'p-text': '▼▼20위▼▼',  'clip-src': 'RepletePlayfulParrotHeyGirl'}
      ],

      count: 0
    }
  },
  computed: {
    //
  },
  mounted() {
    this.init();
  },
  methods: {
    init() {
      this.clickNext();
    },
    getClipSrc() {
      let arr = [this.count++, this.count++];
      if(this.text.length < arr[0] || this.text.length < arr[0]) {
        return null;
      }
      else {
        let arr2 = [this.text[arr[0]], this.text[arr[1]]]
        let ret = [];
        ret.push('<li><p>'+arr2[0]['p-text']+'</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip='+arr2[0]['clip-src']+'&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>');
        ret.push('<li><p>'+arr2[1]['p-text']+'</p><iframe src="https://clips.twitch.tv/embed?autoplay=false&clip='+arr2[1]['clip-src']+'&tt_content=embed&tt_medium=clips_embed" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen="true"></iframe></li>');
        return ret;
      }
    },
    clickNext() {
      var newItem1 = document.createElement("li");
      var newItem2 = document.createElement("li");
      var innerText = this.getClipSrc();
      if(innerText == null) {
        this.showNext = false;
        return;
      }

      newItem1.innerHTML = innerText[0];
      newItem2.innerHTML = innerText[1];

      var list = document.getElementById("clip-list");
      list.insertBefore(newItem1, list.childNodes[list.length-1]);

      var list = document.getElementById("clip-list");
      list.insertBefore(newItem2, list.childNodes[list.length-1]);

      let nextBtn = document.getElementById("show-next");
      list.insertBefore(nextBtn, list.childNodes[list.length-1]);
    }
  }
}
</script>
