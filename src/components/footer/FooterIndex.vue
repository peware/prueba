<template>
    <footer class="footer-index">
        <div class="footer-index-index-icon">
            <img class="footer-icon" src="../../assets/image/icons/footerlogo.png" alt="footer icon">
            <div class="footer-index-text">
                <span class="footer-index-span">Tradeview Markets</span>
                <p class="footer-index-p">| Grand Cayman, KY1-1002, 4th Floor Harbour Place | 103 South</p>
                <p class="footer-index-p">Church St, PO Box 1105</p>
            </div>
            <div class="footer-index-text">
                <span class="footer-index-span">Main Oﬃce: </span>
                <p>+1 345 945 6271</p>
            </div>
            <div class="footer-index-text">
                <span class="footer-index-span">Direct Phone: </span>
                <p>+1 345 946 4532</p>
            </div>
            <div class="footer-index-text">
                <span class="footer-index-span">Website: </span>
                <p>www.tvmarkets.com</p>
            </div>
        </div>
        <div class="footer-index-form">
            <div class="footer-surfup">
                <img src="../../assets/image/icons/footersurfup.png" alt="footer surf">
            </div>
            <span class="footer-form-index-title">Find daily trading insights and undeerstand what is behind the latest waves in financial markets </span>
            <form class="footer-form-subscribe">
                <input class="footer-form-subscribe-text" type="text" value="Enter your email address">
                <input class="footer-form-subscribe-submit" type="submit" value="Subscribe">
            </form>
        </div>
        <FooterIndexSocial/>
        <FooterIndexNotice/>
        <FooterIndexAbout/>
    </footer>
</template>
<script>
import FooterIndexSocial from '../footer/FooterIndexSocial.vue'
import FooterIndexNotice from '../footer/FooterIndexNotice.vue'
import FooterIndexAbout from '../footer/FooterIndexAbout.vue'
  export default {
    name: 'FooterIndex',
    components: {
        FooterIndexSocial,
        FooterIndexNotice,
        FooterIndexAbout
    }
  }; 
</script>