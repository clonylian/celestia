<template>
  <div class="hello">
    <div class="box">
      <div class="head_box">
        <div class="head">
          <img class="head_img" src="../assets/login.svg" alt="">
          <div class="head_1">
            <div class="head_2">
              <div class="head_3"><b>Learn</b> <img class="head_img1" src="../assets/xia.svg"> </div>
              <div class="head_5">
                <div class="head_6">
                  <div class="head_7">
                    <img src="../assets/logo.svg">
                  </div>
                  <div class="head_8">
                    <span>Start here</span>
                    <p>What is Celestia?</p>
                  </div>
                </div>
                <div class="head_6">
                  <div class="head_7">
                    <img src="https://celestia.org/static/92727b0dc8680678449ce97819b3efe9/books.svg">
                  </div>
                  <div class="head_8">
                    <span>Dive deep</span>
                    <p>Dive into modular</p>
                  </div>
                </div>
                <div class="head_6">
                  <div class="head_7">
                    <img src="https://celestia.org/static/f7c5f497afd733bba8dbe370a15eec68/faq.svg">
                  </div>
                  <div class="head_8">
                    <span>learn</span>
                    <p>FAQ</p>
                  </div>
                </div>
                <div class="head_6" style="  border-bottom: 0px #777 solid;">
                  <div class="head_7">
                    <img src="https://celestia.org/static/e420e6bcbda9bde89d6201f866c3bfb3/research.svg">
                  </div>
                  <div class="head_8">
                    <span>Research paper</span>
                    <p>Read the whitepaper</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="head_2">
              <div class="head_4"><b>Bulid</b> <img class="head_img1" src="../assets/xia.svg"></div>
              <div class="head_5">
                <div class="head_6">
                  <div class="head_7">
                    <img src="https://celestia.org/static/9496e8fc124a3d88142407925cd58f50/devnet.svg">
                  </div>
                  <div class="head_8">
                    <span>Developer portal</span>
                    <p>Start with the dev portal</p>
                  </div>
                </div>
                <div class="head_6">
                  <div class="head_7">
                    <img src="https://celestia.org/static/88a4941c09b29e10a49d41d5c8e74e2b/documentation.svg">
                  </div>
                  <div class="head_8">
                    <span>Celestia Documentation</span>
                    <p>Read the docs</p>
                  </div>
                </div>
                <div class="head_6">
                  <div class="head_7">
                    <img src="https://celestia.org/static/3da90207e65500376205c3457f67d43b/github.svg">
                  </div>
                  <div class="head_8">
                    <span>Start here</span>
                    <p>View the GitHub repos</p>
                  </div>
                </div>
              </div>
              <div></div>
            </div>
            <a class="head_2"> Run a node</a>
          </div>
        </div>
        <div class="cen">
          <h1>The first modular blockchain network</h1>
          <p>Celestia is a modular consensus and data network, built to enable anyone to easily deploy their own
            blockchain with minimal overhead.</p>
          <div class="cen_1">
            <a href="https://celestia.org/developer-portal/" class="cen_2">Build modular</a>
            <a href="#one" @click="add" class="cen_3">Connect</a>
          </div>
        </div>
        <div class="mok">
          <div class="mok_1">
            <img src="../assets/1.png">
            <h2>Deploy Fast</h2>
            <p>Deploy your own blockchain in minutes, as easily as a smart contract</p>
          </div>
          <div class="mok_1">
            <img src="../assets/2.png">
            <h2>Deploy Fast</h2>
            <p>Deploy your own blockchain in minutes, as easily as a smart contract</p>
          </div>
          <div class="mok_1">
            <img src="../assets/3.png">
            <h2>Deploy Fast</h2>
            <p>Deploy your own blockchain in minutes, as easily as a smart contract</p>
          </div>
          <div class="mok_1">
            <img src="../assets/4.png">
            <h2>Deploy Fast</h2>
            <p>Deploy your own blockchain in minutes, as easily as a smart contract</p>
          </div>
        </div>
        <div class="cele">
          <div class="cele1"><img src="../assets/quan.svg">
            <h1>Explore Celestia</h1>
          </div>
          <div class="cele2">
            <a href="https://celestia.org/ecosystem" class="cele3">
              <img class="cele5" src="../assets/5.png">
              <h2>Explore the ecosystem</h2>
              <p>Explore Celestia’s ecosystem of rollups and modular infrastructure</p>
              <img class="cele4" src="../assets/28.svg">
            </a>
            <a href="https://celestia.org/what-is-tia" class="cele3">
              <img class="cele5" src="../assets/6.png">
              <h2>Use TIA</h2>
              <p>Pay for blobspace, secure the network, and participate in governance</p>
              <img class="cele4" src="../assets/28.svg">
            </a>
          </div>
          <a href="https://celestia.org/run-a-light-node" class="cele6">
            <img class="cele8" src="../assets/7.png" alt="">
            <div class="cele7">
              <h2> Run a light node</h2>
              <p>Join the first modular data availability network in as little as 2 clicks</p>
            </div>
            <img class="cele9" src="../assets/28.svg">
          </a>
        </div>
        <div class="works">
          <div class="works_1">
            <div class="works_2">
              <img src="../assets/quan.svg">
              <h1>How it works</h1>
            </div>
            <p>Celestia is a minimal blockchain that only orders and publishes transactions but does not execute them. By
              decoupling the consensus and application execution layers, Celestia modularizes the blockchain technology
              stack and unlocks new possibilities for decentralized application builders.</p>
          </div>
          <div class="works_2">
            <div class="works_3">
              <img src="../assets/8.png">
              <h2>Traditional monolithic architecture</h2>
              <li>Developers can only use programming languages supported by chain's execution environment</li>
              <li>All applications run on the same process (the world computer model), with shared gas resources</li>
              <li>Smart contracts cannot be updated without a hard fork</li>
            </div>
            <div class="works_4">
              <img src="../assets/9.png">
              <h2>Traditional monolithic architecture</h2>
              <li>Developers can only use programming languages supported by chain's execution environment</li>
              <li>All applications run on the same process (the world computer model), with shared gas resources</li>
              <li>Smart contracts cannot be updated without a hard fork</li>
            </div>
          </div>
          <div class="works_5">
            <a href="" class="cen_2" style="margin-right: 0;">Learn More</a>
          </div>
        </div>
        <div class="community">
          <div class="works_2">
            <img src="../assets/quan.svg">
            <h1>Join the community</h1>
          </div>
          <p class="community_1">Join the Celestia community online or hang out at one of the grassroots Modular Meetups
          </p>
          <div class="community_2">
            <div class="community_3">
              <div class="community_4">
                <div class="community_5">
                  <img src="../assets/10.png">
                  <div class="community_6">
                    <span>X</span>
                    <p>Read the latest</p>
                  </div>
                </div>
                <div class="community_5">
                  <img src="../assets/11.png">
                  <div class="community_6">
                    <span>Discord</span>
                    <p>Get involved</p>
                  </div>
                </div>
              </div>
              <div class="community_4">
                <div class="community_5">
                  <img src="../assets/12.png">
                  <div class="community_6">
                    <span>Github</span>
                    <p>Build with us</p>
                  </div>
                </div>
                <div class="community_5">
                  <img src="../assets/13.png">
                  <div class="community_6">
                    <span>Telegram</span>
                    <p>Join discussion</p>
                  </div>
                </div>
              </div>
              <div class="community_4">
                <div class="community_5">
                  <img src="../assets/14.png">
                  <div class="community_6">
                    <span>Forum</span>
                    <p>Read Updates</p>
                  </div>
                </div>
                <div class="community_5">
                  <img src="../assets/15.png">
                  <div class="community_6">
                    <span>Reddit</span>
                    <p>See more</p>
                  </div>
                </div>
              </div>
              <a href="https://celestia.org/community/" class="community_7">
                <div class="community_8">
                  <p>Find more</p>
                  <img src="../assets/28.svg">
                </div>
              </a>
            </div>
            <div class="community_9">
              <div class="community_10">
                <img src="../assets/16.jpg">
                <a class="community_11" href="">Modular Summit 2023</a>
              </div>
            </div>
          </div>
        </div>
        <div class="bot">
          <div class="Blog">
            <div class="works_2">
              <img src="../assets/quan.svg">
              <h1>Blog</h1>
            </div>
            <div class="Blog_1">
              <div class="Blog_2">
                <img class="Blog_3" src="../assets/18.jpg">
                <a class="Blog_4" href="">BLOG</a>
                <a class="Blog_5" href="">Concluding the light node challenge</a>
                <a herf="https://blog.celestia.org/concluding-the-light-node-challenge/" class="Blog_6">
                  <p>Read now </p>
                  <img src="../assets/28.svg">
                </a>
              </div>
              <div class="Blog_7">
                <div class="Blog_8">
                  <img class="Blog_9" src="../assets/27.jpg">
                  <div class="Blog_10">
                    <a class="Blog_4" href="">BLOG</a>
                    <a class="Blog_5" href="">2023: A Blockspace Odyssey</a>
                    <a href="https://blog.celestia.org/a-blockspace-odyssey/" class="Blog_6">
                      <p>Read now </p>
                      <img src="../assets/28.svg">
                    </a>
                  </div>
                </div>
                <div class="Blog_8" style="padding-top: 1rem;">
                  <img class="Blog_9" src="../assets/27.jpg">
                  <div class="Blog_10">
                    <a class="Blog_4" href="">BLOG</a>
                    <a class="Blog_5" href="">Introducing the Oolong upgrade to Celestia testnets</a>
                    <a href="https://blog.celestia.org/introducing-the-oolong-upgrade-to-celestia-testnets/"
                      class="Blog_6">
                      <p>Read now </p>
                      <img src="../assets/28.svg">
                    </a>
                  </div>
                </div>
                <div class="Blog_8" style="padding-top: 1rem;">
                  <img class="Blog_9" src="../assets/27.jpg">
                  <div class="Blog_10">
                    <a class="Blog_4" href="">BLOG</a>
                    <a class="Blog_5" href="">Modular data availability for the OP Stack</a>
                    <a href="https://blog.celestia.org/modular-data-availability-for-the-op-stack/" class="Blog_6">
                      <p>Read now </p>
                      <img src="../assets/28.svg">
                    </a>
                  </div>
                </div>
                <div class="Blog_8" style="padding-top: 1rem;">
                  <img class="Blog_9" src="../assets/27.jpg">
                  <div class="Blog_10">
                    <a class="Blog_4" href="">BLOG</a>
                    <a class="Blog_5" href="">Initiating Genesis Drop</a>
                    <a href="https://blog.celestia.org/modular-data-availability-for-the-op-stack/" class="Blog_6">
                      <p>Read now </p>
                      <img src="../assets/28.svg">
                    </a>
                  </div>
                </div>
                <div class="Blog_11">
                  <a class="Blog_6" style=" justify-content: flex-end;">
                    <p>Read now </p>
                    <img src="../assets/28.svg">
                  </a>
                </div>
              </div>
            </div>
          </div>
          <div class="botton">
            <div class="botton_1">
              <h1>Subscribe to our Newsletter</h1>
              <div class="botton_2" style="cursor: pointer;">
                <input placeholder="metamask.tree@gmail.com">
              </div>
              <div class="botton_3">
                <a href="" class="cen_2" style="margin-right: 0;">Subscribe</a>
              </div>
            </div>
            <div class="botton_4">
              <div class="botton_5">
                <h2>Developers</h2>
                <p>Developer portal</p>
                <p>Docs</p>
                <p>Github</p>
              </div>
              <div class="botton_5">
                <h2>Resources</h2>
                <p>Technology</p>
                <p>Glossary</p>
                <p>Blog</p>
                <p>Podcast</p>
                <p>Resources</p>
              </div>
              <div class="botton_5">
                <h2>Misc</h2>
                <p> Brand</p>
                <p>Press</p>
                <p>Ecosystem Jobs</p>
                <p>Terms of Service</p>
                <p>Privacy Policy</p>
              </div>
            </div>
            <div class="botton_6">
              <p>
                Follow us
              </p>
              <a href="https://celestia.org/community" class="botton_7"
                style="cursor: pointer; display: block; ">Community</a>
            </div>
          </div>
          <div class="botton_8">
            <p>This website is maintained by Celestia Labs, trading name of Strange Loop Labs AG, Werdenbergerweg 11, 9490
              Vaduz, Liechtenstein.</p>
            <p>Website designed with by Designatives</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</div></template>

<script>
import { isReadonly } from 'vue';

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  methods: {
    add() {
      main()
    },
  },
  components: { isReadonly }
}
</script>
<style scoped lang="scss">
@font-face {
  font-family: 'one';
  src: url('../assets/one.otf');
}

@font-face {
  font-family: 'two';
  src: url('../assets/two.otf');
}

@font-face {
  font-family: 'one';
  src: url('../assets/three.ttf');
}

@font-face {
  font-family: 'four';
  src: url('../assets/four.ttf');
}

@font-face {
  font-family: 'five';
  src: url('../assets/five.ttf');
}

@font-face {
  font-family: 'six';
  src: url('../assets/six.otf');
}

@font-face {
  font-family: 'even';
  src: url('../assets/even.otf');
}



.box {
  width: 100%;
  background-color: white;
}

.head_box {
  width: 100%;
  height: 100vh;
  margin: 0 auto;
  background-image: url('../assets/24.png');
  background-size: 100% 100%;
  background-repeat: no-repeat;
}

.head {
  width: 80%;
  height: 6rem;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.head_1 {
  display: flex;
  font-family: six;
  // font-weight: 900;
}

.head_img {
  width: 200px;
  height: 50px;
}

.head_img1 {
  width: 20px;
  height: 20px;
}

.head_2 {
  margin-right: 1.5rem;
}

.head_3 {
  display: flex;
  align-items: center;
  margin-right: 0.5rem;
  position: relative;
  top: 1%;
}

.head_4 {
  display: flex;
  align-items: center
}

.head_5 {
  width: 20rem;
  backdrop-filter: blur(10px);
  background-color: hsla(0, 0%, 100%, .7);
  background: hsla(0, 0%, 98%, .95);
  border-radius: 10px;
  max-width: 360px;
  // display: flex;
  display: none;
  flex-direction: column;
  position: absolute;
  top: 10%;
  border-radius: 15px;
}

.head_3:hover+.head_5 {
  display: block;
  /* 鼠标悬浮时显示 */
}

.head_4:hover+.head_5 {
  display: block;
  /* 鼠标悬浮时显示 */
}

.head_6 {
  padding: 1rem 0 1rem 1rem;
  width: 100%;
  display: flex;
  align-items: center;
  border-bottom: 1px solid rgba(0, 0, 0, .07);
}

.head_6:hover {
  color: #7b2bf9;
}

.head_7:hover {
  background-color: #7b2bf9;
}

.head_7 {
  width: 30px;
  height: 30px;
  border-radius: 30px;
  background-color: black;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-right: 1rem;
}

.head_8>span {
  color: #777;
  font-size: 12px;
  letter-spacing: 0;
  line-height: 1.25em;
}

.head_8>p {
  font-size: 14px;
}

.cen {
  width: 80%;
  max-width: 1340px;
  height: 40rem;
  padding-top: 6rem;
  margin: 0 auto;
  background: url('https://celestia.org/static/home-hero-image-a13233e4c024277a50abe3188f975373.svg') no-repeat scroll 100% transparent;
}

.cen>h1 {
  max-width: 1200px;
  margin-bottom: 30px;
  width: 80%;
  color: #000;
  display: inline-block;
  font-family: six;
  font-size: 106px;
  font-weight: 900;
  letter-spacing: 1.38px;
  line-height: 106px;
}

.cen>p {
  width: 40%;
  color: #000;
  font-family: six;
  font-size: 18px;
  font-weight: 500;
  letter-spacing: .22px;
  line-height: 26px;
  margin-bottom: 50px;
}

.cen_1 {
  width: 20rem;
  display: flex;
}

.cen_2 {
  padding: 1rem;
  color: white;
  font-size: 14px;
  font-weight: 900;
  font-family: six;
  background-color: #000;
  margin-right: 2rem;

  border-radius: 5px;

}

.cen_3 {
  padding: 1rem;
  color: #000;
  font-size: 14px;
  font-weight: 900;
  font-family: six;
  border: 1px #000 solid;
  border-radius: 5px;
  background-color: white;
}

.mok {
  max-width: 1800px;
  width: 100%;
  display: flex;
  margin: 0 auto;
  justify-content: space-evenly;
  padding-bottom: 5rem;
}

.mok_1 {
  width: 24rem;
  padding: 35px 25px;
  background: hsla(0, 0%, 97%, .5);
  border: 1px solid rgba(0, 0, 0, .04);
  border-radius: 15px;
  display: flex;
  flex-direction: column;
  margin-top: 3rem;
}

.mok_1>img {
  width: 170px;
  height: 170px;
}

.mok_1>h2 {
  color: #000;
  font-family: six;
  font-size: 32px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: 40px;
  margin-bottom: 20px;
}

.mok_1>p {
  font-family: one;
  color: #414141;
}

.cele {
  width: 80%;
  margin: 0 auto;
}

.cele1 {
  display: flex;
  justify-content: center;
  margin-bottom: 5rem;
}

.cele1>h1 {
  font-size: 75px;
  font-family: six;
  font-weight: 900;
}

.cele2 {
  width: 100%;
  display: flex;
  justify-content: space-around;
}

.cele3 {
  width: 45%;
  padding: 35px 25px;
  background: hsla(0, 0%, 97%, .5);
  border: 1px solid rgba(0, 0, 0, .04);
  border-radius: 15px;
  display: flex;
  flex-direction: column;
  margin-top: 3rem;
  position: relative;
}

.cele3>h2 {
  color: #000;
  font-family: six;
  font-size: 32px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: 40px;
  margin-bottom: 20px;
  margin-top: 3rem;
}

.cele3>p {
  font-family: one;
  color: #414141;
  font-size: 18px;
  line-height: 25px;
}

.cele5 {
  width: 250px;
  height: 160px;
}

.cele4 {
  position: absolute;
  width: 60px;
  height: 60px;
  left: 85%;
}

.cele9 {
  position: absolute;
  width: 60px;
  height: 60px;
  left: 90%;
}

.cele6 {
  justify-content: space-around;
  display: flex;
  width: 95%;
  margin: 3rem auto;
  padding: 35px 25px;
  background: hsla(0, 0%, 97%, 0.5);
  border: 1px solid rgba(0, 0, 0, 0.04);
  position: relative;
  border-radius: 15px;
}

.cele8 {
  width: 405px;
  height: 285px;
}

.cele7 {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.cele7>h2 {
  color: #000;
  font-family: six;
  font-size: 32px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: 40px;
  margin-bottom: 20px;
  margin-top: 3rem;
}

.cele7>p {
  font-family: one;
  color: #414141;
  font-size: 18px;
  line-height: 25px;
}

.works {
  width: 75%;
  margin: 0 auto;
}

.works_2>h1 {
  color: #000;
  font-family: six;
  font-size: 70px;
  font-weight: 700;
  letter-spacing: .2px;
  line-height: 74px;
  position: relative;

}

.works_2>img {
  position: absolute;
  left: 11%;
}

.works_2 {
  display: flex;
}

.works_1>p {
  color: #000;
  font-family: one;
  font-size: 18px;
  font-weight: 300;
  letter-spacing: 0;
  line-height: 27px;
  margin: 1rem 0 2rem 0;
}

.works_2 {
  width: 100%;
  display: flex;
  justify-content: space-between;
}

.works_3 {
  width: 48%;
  background: #f7f7f7;
  border: none;
  border-radius: 15px;
  padding: 80px 60px 60px;
}

.works_3>img {
  width: 500px;
  height: 500px;
}

.works_3>h2 {
  color: #000;
  font-family: six;
  font-size: 40px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: 48px;
  margin-bottom: 20px;
}

.works_3>li {
  font-family: one;
  margin-bottom: 25px;
  padding-left: 25px;
  font-size: 18px;
  opacity: 0.8;
}

.works_4 {
  width: 48%;
  background-image: linear-gradient(220deg, #f5f5f5 21%, #f8e2b7 70%, #ffb0b0);
  border: none;
  border-radius: 15px;
  padding: 80px 60px 60px;
}

.works_4>img {
  width: 500px;
  height: 500px;
}


.works_4>h2 {
  color: #000;
  font-family: six;
  font-size: 40px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: 48px;
  margin-bottom: 20px;
}

.works_4>li {
  font-family: one;
  margin-bottom: 25px;
  padding-left: 25px;
  font-size: 18px;
  opacity: 0.8;
}

.works_5 {
  display: flex;
  justify-content: center;
  margin-top: 2rem;
}

.community {
  width: 75%;
  margin: 0 auto;
  padding-top: 8rem;
}

.community_1 {
  color: #000;
  font-family: one;
  font-size: 16px;
  font-weight: 300;
  letter-spacing: 0;
  line-height: 27px;
  margin: 1rem 0 3rem 0;
}

.community_2 {
  width: 100%;
  display: flex;
  justify-content: space-between;
}

.community_3 {
  width: 48%;
  background-color: #fff;
  border: 1px solid #d9d9d9;
  border-radius: 8px;
  display: flex;
  flex-direction: column;
  height: 100%;
  justify-content: space-between;
  padding: 55px 50px 45px 45px;
}

.community_4 {
  width: 100%;
  display: flex;
  margin-bottom: 2rem;
  justify-content: space-between;
}

.community_5>span {
  color: #000;
  font-family: six;
  font-size: 40px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: 48px;
  margin-bottom: 20px;
}

.community_5 {
  width: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.community_5>img {
  width: 40px;
  height: 40px;
  margin-right: 1rem;
}

.community_6>span {
  font-family: six;
  font-weight: 900;
}

.community_6>p {
  color: #000;
  font-family: one;
  font-size: 13px;
  font-weight: 300;
  letter-spacing: 0;
  line-height: 27px;
  // margin: 1rem 0 2rem 0;
}

.community_7 {
  width: 100%;
  display: flex;
  margin-top: 6rem;
}

.community_8 {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: flex-end;
  font-size: 14px;
  font-family: six;
  font-weight: 900;
}

.community_8>img {
  width: 40px;
  height: 40px;
}

.community_8>p:hover {
  color: #7b2bf9;
}

.community_9 {
  width: 50%;
}

.community_10 {
  position: relative;
  top: 0%;
}

.community_10>img {
  width: 642px;
  height: 480px;
}

.community_11 {
  position: absolute;
  top: 85%;
  left: 5%;
  border-radius: 30px;
  font-family: six;
  font-weight: 900;
  font-size: 14px;
  color: white;
  padding: 1rem 1.5rem 1rem 1.5rem;
  backdrop-filter: blur(25px);
  background: hsla(0, 0%, 100%, .3);
  border: unset;
}

.bot {
  width: 100%;
  background-image: url('../assets/25.png');
  background-repeat: no-repeat;
  background-size: 100% 100%;
}

.Blog {
  width: 75%;
  margin: 0 auto;
  padding-top: 8rem;

}

.Blog_1 {
  width: 100%;
  display: flex;
  margin-top: 3rem;
}

.Blog_2 {
  width: 50%;
  display: flex;
  flex-direction: column
}

.Blog_3 {
  width: 710px;
  height: 370px;
  border-radius: 10px;
}

.Blog_4 {
  color: #525252;
  font-family: six;
  font-weight: 900;
  font-size: 14px;
  margin: 1rem 0 1rem 0;
}

.Blog_5 {
  color: #000;
  font-family: six;
  font-size: 32px;
  font-weight: 900;
  letter-spacing: 0;
  line-height: 40px;
  margin-bottom: 15px;
}

.Blog_6 {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  font-size: 16px;
  font-family: six;
  font-weight: 900;
}

.Blog_6>img {
  width: 30px;
  height: 30px;
}

.Blog_7 {
  width: 50%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.Blog_8 {
  display: flex;
  border-bottom: 1px;
  padding-bottom: 2rem;
  border-bottom: 1px solid hsla(0, 0%, 59%, .18);
}

.Blog_8>img {
  width: 100px;
  height: 50px;
  border-top-right-radius: 5px;
  border-top-left-radius: 5px;
}

.Blog_9 {
  margin-top: 1rem;
  margin-left: 2rem;
  margin-right: 2rem;
}

.Blog_10 {
  display: flex;
  flex-direction: column;
}

.Blog_11 {
  width: 80%;
  margin: 0 autos;
  display: flex;
}

.botton {
  width: 80%;
  padding-top: 5rem;
  margin: 0 auto;
  display: flex;

}

.botton_1 {
  width: 30rem;
  // border: 1px red solid;
  display: flex;
  flex-direction: column;
}

.botton_1>h1 {
  color: #fff;
  font-family: six;
  font-size: 40px;
  line-height: 48px;
  font-weight: 900;
  letter-spacing: 0;
  margin-bottom: 20px;
}

.botton_2 {
  width: 100%;
  background-color: white;
  padding: 1.5rem 0 1.5rem 1.5rem;
  border-radius: 5px;

}

.botton_2>input {
  border: none;
  outline: none;

}

.botton_3 {
  margin: 1.5rem 0 1.5rem 0;
}

.botton_4 {
  display: flex;
}

.botton_5 {
  margin-left: 5rem;
  color: white;
  font-family: six
}

.botton_5>h2 {
  font-weight: 900;
  font-size: 24px;
  margin-bottom: 1.5rem;
}

.botton_5>p {
  line-height: 35px;
}

.botton_6 {
  margin-left: 8rem;
}

.botton_6>p {
  font-weight: 900;
  font-family: six;
  color: white;
  font-size: 20px;
}

.botton_7 {
  margin-top: 2rem;
  padding: 1rem 2rem;
  font-family: six;
  font-weight: 900;
  border-radius: 5px;
  background: #ebebeb;
  color: #000;
}

.botton_8 {
  padding-top: 3rem;
  padding-bottom: 5rem;
  width: 60%;
  margin: 0 auto;
  color: white;
  font-family: six;
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.botton_8>p:nth-child(1) {
  font-size: 1px;
  font-style: normal;
  font-weight: 500;
  font-weight: 400;
  line-height: normal;
  max-width: 500px;
  opacity: 0.75;
  text-align: center;
  margin-bottom: 2rem;
}

@media (max-width: 600px) {
  .box {
    width: 100vw;
  }

  .head_1 {
    display: none;
  }

  .cen {
    width: 100%;
    background-size: 70vw;
    padding-top: 60vw;
    background-position: 30% 0%;
    // background-image: none;
    text-align: center;
  }

  .cen>h1 {
    font-size: 20px;
    line-height: 29px;
  }

  .cen>p {
    width: 100%;
  }

  .cen_1 {
    width: 100%;
    justify-content: center;
  }

  .mok {
    flex-direction: column;
  }

  .mok_1 {
    align-items: center;
    text-align: center;
  }

  .cele1>h1 {
    font-size: 40px;
  }

  .cele2 {
    flex-direction: column;
  }

  .cele3 {
    width: 100%;
  }

  .cele4 {
    left: 75%;
  }

  .cele5 {
    width: 200px;
    height: 120px;
  }

  .cele6 {
    flex-direction: column;
  }

  .cele8 {
    width: 207px;
    height: 130px;
  }

  .cele9 {
    display: none;
  }

  .works_2>h1 {
    font-size: 40px;
    text-align: center;
  }

  .works_1>p {
    font-size: 12px;
  }

  .works_2 {
    flex-direction: column;
  }

  .works_3 {
    width: 100%;
    background: #f7f7f7;
    border: none;
    border-radius: 15px;
    padding: 66px 12px 60px;
  }

  .works_3>img {
    width: 250px;
    height: 250px;
  }

  .works_4 {
    width: 100%;
    background: #f7f7f7;
    border: none;
    border-radius: 15px;
    padding: 66px 12px 60px;
  }

  .works_4>img {
    width: 250px;
    height: 250px;
  }

  .community_2 {
    flex-direction: column;
  }

  .community_3 {
    width: 100%;
    padding: 52px 18px 38px 18px;

  }

  .community_4 {
    flex-direction: column;
  }

  .community_10>img {
    width: 250px;
    height: 200px;
  }

  .community_11 {
    display: none;
  }

  .Blog_1 {
    flex-direction: column;
    align-items: center
  }

  .Blog_2 {
    width: 100%;
    align-items: center;
  }

  .Blog_3 {
    width: 250px;
    height: 150px;
  }

  .Blog_5 {
    text-align: center;
  }

  .Blog_6 {

    justify-content: center
  }

  .Blog_9 {
    display: none;
  }

  .Blog_10 {
    align-items: center
  }

  .botton {
    width: 100%;
    flex-direction: column;
  }

  .botton_1 {
    text-align: center;
    width: 100%;
    align-items: center
  }

  .botton_4 {
    flex-direction: column;
    text-align: center;
  }

  .botton_5 {
    margin-left: 0;
  }

  .botton_6 {
    text-align: center;
    margin-left: 0;
    margin-top: 3rem;
  }

  .cele {
    width: 100%;
    text-align: center;
  }

  .cele1>img {
    display: none;
  }

  .head {
    justify-content: center;
    margin-bottom: 3rem;
  }
}</style>
