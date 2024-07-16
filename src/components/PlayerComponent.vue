<template>
    <section class="hero is-small has-background-white">
        <div class="columns">
            <div class="column">
                <div class="hero-body">
                    <p class="title has-text-dark">El podcast del programador con invitados especiales</p>
                    <p class="subtitle">De <em class="is-clickable"><b>kkissta</b></em>, <em
                            class="is-clickable"><b>funalito</b></em>, <em class="is-clickable"><b>El rincón de
                                fulanita</b></em>
                    </p>
                </div>
            </div>
            <div class="column is-1 my-auto">
                <div class="container ">
                    <div class="columns">
                        <div class="colunmn">
                            <figure class="image is-32x32">
                                <img class="is-clickable" :src="playBtn" alt="Placeholder image" />
                            </figure>
                        </div>
                        <div class="colunmn my-auto ml-5">
                            <figure class="image" style="width: 23px;">
                                <img class="is-clickable" :src="likeOutBtn" alt="Placeholder image" />
                            </figure>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>
</template>


<script>
import playBtnSvg from '@/assets/playBtn.svg'
import likeSvg from '@/assets/like.svg'
import likeOutSvg from '@/assets/like-out.svg'

export default {
  name: 'App',
  data() {
    return {
      playBtn: playBtnSvg,
      likeBtn: likeSvg,
      likeOutBtn: likeOutSvg
    }
  }
}
</script>