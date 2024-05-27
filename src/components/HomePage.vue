<template>
    <div class="body">

        <div class="herosection">
            

            
            <div class="image">
                <div class="veil"></div>
                    <img src="../assets/sideprojectpic.jpg" alt="">
             </div>


                <div class="textsection">
                    <div class="creating">
                        <div>
                            <p ref="creating1">C</p>

                        </div>
                        <div>
                            <p ref="creating2">R</p>

                        </div>
                        <div>
                            <p ref="creating3">E</p>

                        </div>
                        <div>
                            <p ref="creating4">A</p>

                        </div>
                        <div>
                            <p ref="creating5">T</p>

                        </div>
                        <div>
                            <p ref="creating6">I</p>

                        </div>
                        <div>
                            <p ref="creating7">N</p>

                        </div>
                        <div>
                            <p ref="creating8">G</p>

                        </div>

                        <!-- <p class="creating" ref="creating">CREATING</p> -->

                    </div>
                    <div class="artful" ref="artful">
                        <div>
                            <p ref="creating9">a</p>

                        </div>
                        <div>
                            <p ref="creating10">r</p>

                        </div>
                        <div>
                            <p ref="creating11">t</p>

                        </div>
                        <div>
                            <p ref="creating12">f</p>

                        </div>
                        <div>
                            <p ref="creating13">u</p>

                        </div>
                        <div>
                            <p ref="creating14">l</p>

                        </div>

                    </div>
                    <div class="digital" ref="digital">
                        <div>
                            <p ref="creating15">d</p>

                        </div>
                        <div>
                            <p ref="creating17">i</p>

                        </div>
                        <div>
                            <p ref="creating18">g</p>

                        </div>
                        <div>
                            <p ref="creating19">i</p>

                        </div>
                        <div>
                            <p ref="creating20">t</p>

                        </div>
                        <div>
                            <p ref="creating21">a</p>

                        </div>
                        <div>
                            <p ref="creating22">l</p>

                        </div>

                    </div>
                    <div class="journeys" ref="journeys">
                        <div>
                            <p ref="creating23">J</p>

                        </div>
                        <div>
                            <p ref="creating24">O</p>

                        </div>
                        <div>
                            <p ref="creating25">U</p>

                        </div>
                        <div>
                            <p ref="creating26">R</p>

                        </div>
                        <div>
                            <p ref="creating27">N</p>

                        </div>
                        <div>
                            <p ref="creating28">E</p>

                        </div>
                        <div>
                            <p ref="creating29">Y</p>

                        </div>
                        <div>
                            <p ref="creating30">S</p>

                        </div>
                    </div>
                    
                    <div class="bottomtext">
                        <div class="bottomtext1">
                            <p ref="bottomtext2">Crafting</p>
                            <p ref="bottomtext3">digital</p>
                            <p ref="bottomtext4">masterpieces</p>
                            <p ref="bottomtext5">that</p>
                            <p ref="bottomtext30">blend</p>
                            <p ref="bottomtext31">beauty</p>
                            <p ref="bottomtext32">and</p>
                            <p ref="bottomtext7">functionality.</p>


                        </div>
                        <div class="bottomtext2">
                            <p ref="bottomtext8">Let's</p>
                            <p ref="bottomtext9">build</p>
                            <p ref="bottomtext10">a</p>
                            <p ref="bottomtext11">website</p>
                            <p ref="bottomtext12">that</p>
                            <p ref="bottomtext13">tells</p>
                            <p ref="bottomtext14">your</p>
                            <p ref="bottomtext15">story,</p>
                            <p ref="bottomtext16">captivates</p>
                            <p ref="bottomtext17">your</p>
                            <p ref="bottomtext18">audience.</p>

                        </div>
                        <div class="bottomtext3">
                            <p ref="bottomtext19">"Your</p>
                            <p ref="bottomtext20">vision,</p>
                            <p ref="bottomtext21">our</p>
                            <p ref="bottomtext22">creation.</p>
                            <p ref="bottomtext23">Crafting</p>
                            <p ref="bottomtext24">unique,</p>
                            <p ref="bottomtext25">stunning</p>
                            <p ref="bottomtext26">websites</p>
                            <p ref="bottomtext27">that</p>
                            <p ref="bottomtext28">inspire</p>
                            <p ref="bottomtext29">actions</p>


                        </div>

                        
                    </div>

                </div>


            </div>



            
    </div>

</template>

<style lang="scss" scoped>
.body {
    height: fit-content;
    width: 100vw;
    overflow: hidden;
    .herosection {
        // position: relative;
        height: 100vh;
        width: 100vw;
        overflow: hidden;
        background-color: black;
        
        
        .image {
            position: absolute;
            z-index: 1;
            width: 100vw;
            height: 100vh;
            overflow: hidden;
            
            .veil {
                position: absolute;
                z-index: 2;
    
                background-color: hsla(0, 0%, 0%, 0.804);
                width: 100vw;
                height: 100vh;
        
            }
            img {
                position: relative;
                top: 2rem;
                width: 120%;
                height: auto;
                rotate: 40deg;
                // object-fit: cover;

            }
        }
        .textsection {
            position: relative;
            z-index: 3;
            // border: solid red;
            width: 100vw;
            height: 100vh;
            color: rgba(255, 255, 255, 0.413);

            .creating {
                position: absolute;
                top: 200px;
                left: 347px;
                display: flex;
                font-size: 130px;
                div {
                    overflow: hidden;
                    // position: relative;

                    p {
                        transform: translateX(6.5rem);
                        // position: relative;
                        // right: -3rem;
                    }
                }


                :nth-child(5) {
                    margin-left: -1rem;
                }

            }
            .artful {

                // border: solid red;
                transform: translateX(-4rem);
                position: absolute;
                top: 324px;
                left: 468px;
                display: flex;
                font-size: 130px;
                div {
                    overflow: hidden;
                    padding-right: 0.5rem;
                    padding-left: 0.25rem;


                    // position: relative;
                    
                    p {
                        transform: translateX(6.5rem);
                        font-style: italic;

                        // position: relative;
                        // right: -3rem;
                    }
                }
                
                
            }
            .digital {
                position: absolute;
                
                transform: translateX(4rem);
                top: 476px;
                right: 488px;
                font-size: 130px;
                
                display: flex;
                div {
                    overflow: hidden;
                    // width: 6.5rem;
                    padding-right: 0.5rem;
                    padding-left: 0.25rem;
                    // border: solid;
                    // position: relative;
                    
                    p {
                        transform: translateX(6.5rem);
                        font-style: italic;

                        // position: relative;
                        // right: -3rem;
                    }
                }
            }

            .journeys {
                // transform: translateX(-2rem);
                display: flex;

                position: absolute;
                top: 631px;
                right: 360px;
                font-size: 130px;

                div {
                    overflow: hidden;
                    // position: relative;
                    
                    p {
                        transform: translateX(6.5rem);
                        // position: relative;
                        // right: -3rem;
                    }
                }
            }
            .bottomtext {
                // border: solid red;
                position: absolute;
                top: 799px;
                left: 83px;
                font-size: 20px;

                div {
                    display: flex;
                    gap: 5px;
                    overflow-y: hidden;

                    p {
                        transform: translateY(1.5rem);
                    }
                }

            }
        }
    }

    .section2 {
        width: 100vw;
        height: 100rem;
        background-color: grey;

    }
}

</style>

<script setup>

import { ref, onMounted, onBeforeUnmount, onUnmounted } from 'vue';


import gsap from 'gsap';
import ScrollTrigger from 'gsap/ScrollTrigger';
gsap.registerPlugin(ScrollTrigger);


const creating1 = ref(null);
const creating2 = ref(null);
const creating3 = ref(null);
const creating4 = ref(null);
const creating5 = ref(null);
const creating6 = ref(null);
const creating7 = ref(null);
const creating8 = ref(null);

const artful = ref(null);
const creating9 = ref(null);
const creating10 = ref(null);
const creating11 = ref(null);
const creating12 = ref(null);
const creating13 = ref(null);
const creating14 = ref(null);


const digital = ref(null);
const creating15 = ref(null);
const creating17 = ref(null);
const creating18 = ref(null);
const creating19 = ref(null);
const creating20 = ref(null);
const creating21 = ref(null);
const creating22 = ref(null);


const creating23 = ref(null);
const creating24 = ref(null);
const creating25 = ref(null);
const creating26 = ref(null);
const creating27 = ref(null);
const creating28 = ref(null);
const creating29 = ref(null);
const creating30 = ref(null);



const bottomtext2 = ref(null);
const bottomtext3 = ref(null);
const bottomtext4 = ref(null);
const bottomtext5 = ref(null);
const bottomtext6 = ref(null);
const bottomtext30 = ref(null);
const bottomtext31 = ref(null);
const bottomtext32 = ref(null);
const bottomtext7 = ref(null);


const bottomtext8 = ref(null);
const bottomtext9 = ref(null);
const bottomtext10 = ref(null);
const bottomtext11 = ref(null);
const bottomtext12 = ref(null);
const bottomtext13 = ref(null);
const bottomtext14 = ref(null);
const bottomtext15 = ref(null);
const bottomtext16 = ref(null);
const bottomtext17 = ref(null);
const bottomtext18 = ref(null);

const bottomtext19 = ref(null);
const bottomtext20 = ref(null);
const bottomtext21 = ref(null);
const bottomtext22 = ref(null);
const bottomtext23 = ref(null);
const bottomtext24 = ref(null);
const bottomtext25 = ref(null);
const bottomtext26 = ref(null);
const bottomtext27 = ref(null);
const bottomtext28 = ref(null);
const bottomtext29 = ref(null);








onMounted(() => {
    const tl = gsap.timeline({ defaults: { duration: 0.2, ease: 'power4.out' }, delay: 1.85 });
    const tl2 = gsap.timeline({ defaults: { duration: 0.2, ease: 'power4.out' }, delay: 1.45 }); //"cubic-bezier(.81,-0.42,.74,.89)" }
    const tl3 = gsap.timeline({ defaults: { duration: 0.2, ease: 'power4.out' }, delay: 2.45 }); //"cubic-bezier(.81,-0.42,.74,.89)" }
    const tl4 = gsap.timeline({ defaults: { duration: 0.2, ease: 'power4.out' }, delay: 2.5 }); //"cubic-bezier(.81,-0.42,.74,.89)" }
    const tl5 = gsap.timeline({ defaults: { duration: 0.2, ease: 'power4.out' }, delay: 2.6 }); //"cubic-bezier(.81,-0.42,.74,.89)" }


    tl.to(creating1.value, { x: 0, duration: 0.35,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl.to(creating2.value, { x: 0, duration: 0.45, },   0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating3.value, { x: 0, duration: 0.55, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating4.value, { x: 0, duration: 0.65, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating5.value, { x: 0, duration: 0.75, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating6.value, { x: 0, duration: 0.85, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating7.value, { x: 0, duration: 0.95, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating8.value, { x: 0, duration: 1.05, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      
      tl2.to(artful.value, { x: 0, duration: 0.7,  },  1); // Start at the beginning of the timeline (after the 1 second delay)
      tl.to(creating9.value, { x: 0, duration: 0.35,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl.to(creating10.value, { x: 0, duration: 0.45, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating11.value, { x: 0, duration: 0.55, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating12.value, { x: 0, duration: 0.65, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating13.value, { x: 0, duration: 0.75, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating14.value, { x: 0, duration: 0.85, }, 0); // Start at the same time as creating1 (after the 1 second delay)



      tl2.to(digital.value, { x: 0, duration: 0.7,  },  1); // Start at the beginning of the timeline (after the 1 second delay)

      tl.to(creating15.value, { x: 0, duration: 0.35,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl.to(creating17.value, { x: 0, duration: 0.45, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating18.value, { x: 0, duration: 0.55, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating19.value, { x: 0, duration: 0.65, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating20.value, { x: 0, duration: 0.75, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating21.value, { x: 0, duration: 0.85, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating22.value, { x: 0, duration: 0.95, }, 0); // Start at the same time as creating1 (after the 1 second delay)

      tl.to(creating23.value, { x: 0, duration: 0.35,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl.to(creating24.value, { x: 0, duration: 0.45, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating25.value, { x: 0, duration: 0.55, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating26.value, { x: 0, duration: 0.65, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating27.value, { x: 0, duration: 0.75, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating28.value, { x: 0, duration: 0.85, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating29.value, { x: 0, duration: 0.95, }, 0); // Start at the same time as creating1 (after the 1 second delay)
      tl.to(creating30.value, { x: 0, duration: 1.05, }, 0); // Start at the same time as creating1 (after the 1 second delay)



      tl3.to(bottomtext2.value, { y: 0, duration: 0.6,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl3.to(bottomtext3.value, { y: 0, duration: 0.7,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl3.to(bottomtext4.value, { y: 0, duration: 0.8  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl3.to(bottomtext5.value, { y: 0, duration: 0.9,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl3.to(bottomtext6.value, { y: 0, duration: 1,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl3.to(bottomtext31.value, { y: 0, duration: 1.1,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl3.to(bottomtext30.value, { y: 0, duration: 1.12,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl3.to(bottomtext32.value, { y: 0, duration: 1.14,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl3.to(bottomtext7.value, { y: 0, duration: 1.16,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      
      tl4.to(bottomtext8.value, { y: 0, duration: 0.6,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl4.to(bottomtext9.value, { y: 0, duration: 0.7,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl4.to(bottomtext10.value, { y: 0, duration: 0.8,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl4.to(bottomtext11.value, { y: 0, duration: 0.9,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl4.to(bottomtext12.value, { y: 0, duration: 1,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl4.to(bottomtext13.value, { y: 0, duration: 1.1,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl4.to(bottomtext14.value, { y: 0, duration: 1.12,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl4.to(bottomtext15.value, { y: 0, duration: 1.14,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl4.to(bottomtext16.value, { y: 0, duration: 1.16,  },  0); // Start at the beginning of the timeline (after the 1 second delay).value, { y: 0, duration: 0.95,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl4.to(bottomtext17.value, { y: 0, duration: 1.18,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl4.to(bottomtext18.value, { y: 0, duration: 1.2,  },  0); // Start at the beginning of the timeline (after the 1 second delay)

      tl5.to(bottomtext19.value, { y: 0, duration: 0.6,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl5.to(bottomtext20.value, { y: 0, duration: 0.7,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl5.to(bottomtext21.value, { y: 0, duration: 0.8,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl5.to(bottomtext22.value, { y: 0, duration: 0.9,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl5.to(bottomtext23.value, { y: 0, duration: 1,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl5.to(bottomtext24.value, { y: 0, duration: 1.1,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl5.to(bottomtext25.value, { y: 0, duration: 1.12,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl5.to(bottomtext26.value, { y: 0, duration: 1.14,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl5.to(bottomtext27.value, { y: 0, duration: 1.16,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl5.to(bottomtext28.value, { y: 0, duration: 1.18,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      tl5.to(bottomtext29.value, { y: 0, duration: 1.2,  },  0); // Start at the beginning of the timeline (after the 1 second delay)
      


});



</script>