<template lang="pug">
  section.question-container

    h1.question-answer-title-1.question-answer-title.centered(v-if="question_number == 1") QUI DORT DANS UN OPERA POUR PECHO?

    h1.question-answer-title-2.question-answer-title.centered(v-if="question_number == 2") QUI A UN SOURIRE À LA COLGATE ?

    h1.question-answer-title-3.question-answer-title.centered(v-if="question_number == 3") QUI EST LE PLUS GRAND DE TOUS LES VAMPIRES ?

    h1.question-answer-title-4.question-answer-title.centered(v-if="question_number == 4") QUI N'AVAIT PAS D'AMIS ?

    h1.question-answer-title-5.question-answer-title.centered(v-if="question_number == 5") QUI EST CONNU POUR SES DEUX PERSONNALITE ?

    h1.question-answer-title-6.question-answer-title.centered(v-if="question_number == 6") Qui a toujours ses papiers sur lui ?

    h1.question-answer-title-7.question-answer-title.centered(v-if="question_number == 7") Qui est le chat le plus mÉCHANT ?

    h1.question-answer-title-8.question-answer-title.centered(v-if="question_number == 8") Qui est une balance ?

    h1.question-answer-title-9.question-answer-title.centered(v-if="question_number == 9") Qui n’est pas alle Chez l’esthEticienne depuis 3 mois ?

    h1.question-answer-title-10.question-answer-title.centered(v-if="question_number == 10") 
      span.relative-container 
        | QUI ADORE 
        img.crack1.crack(src="static/images/crack1.svg")

      span.relative-container
        | REGARDER LES FILLES 
        img.crack3.crack(src="static/images/crack3.svg")
        img.crack4.crack(src="static/images/crack4.svg") 

      span.relative-container
        | SOUS LA
        img.crack5.crack(src="static/images/crack5.svg")

      span.relative-container
        | DOUCHE ? 
        img.crack2.crack(src="static/images/crack2.svg")

    .link-container
      router-link.reponse.reponse-1(v-if="question_number == 1" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Les rats d'Opéra
      router-link.reponse.reponse-1(v-if="question_number == 1" :to="{path: '/reponse/' + question_number}" @click.native="correctAnswer") Le fantôme de l'Opéra
      router-link.reponse.reponse-1(v-if="question_number == 1" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") La danseuse étoilée

      router-link.reponse.reponse-2(v-if="question_number == 2" :to="{path: '/reponse/' + question_number}" @click.native="correctAnswer") l'Homme qui rit
      router-link.reponse.reponse-2(v-if="question_number == 2" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Je préfère Signal
      router-link.reponse.reponse-2(v-if="question_number == 2" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Miley Cirus

      router-link.reponse.reponse-3(v-if="question_number == 3" :to="{path: '/reponse/' + question_number}" @click.native="correctAnswer") Dracula
      router-link.reponse.reponse-3(v-if="question_number == 3" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Edward Collen
      router-link.reponse.reponse-3(v-if="question_number == 3" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Le petit vampire

      router-link.reponse.reponse-4(v-if="question_number == 4" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Remi
      router-link.reponse.reponse-4(v-if="question_number == 4" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Ton ami imaginaire
      router-link.reponse.reponse-4(v-if="question_number == 4" :to="{path: '/reponse/' + question_number}" @click.native="correctAnswer") Frankenstein

      router-link.reponse.reponse-5(v-if="question_number == 5" :to="{path: '/reponse/' + question_number}" @click.native="correctAnswer") Dr Jekyll & Mr Hyde  
      router-link.reponse.reponse-5(v-if="question_number == 5" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Dr Jekyl
      router-link.reponse.reponse-5(v-if="question_number == 5" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Mr Hide

      router-link.reponse.reponse-6(v-if="question_number == 6" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Un gendarme   
      router-link.reponse.reponse-6(v-if="question_number == 6" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Ton petit cousin fier d’être majeur
      router-link.reponse.reponse-6(v-if="question_number == 6" :to="{path: '/reponse/' + question_number}" @click.native="correctAnswer") La momie

      router-link.reponse.reponse-7(v-if="question_number == 7" :to="{path: '/reponse/' + question_number}" @click.native="correctAnswer") Le Chat noir  
      router-link.reponse.reponse-7(v-if="question_number == 7" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Nyan Cat
      router-link.reponse.reponse-7(v-if="question_number == 7" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Je donne ma langue au chat

      router-link.reponse.reponse-8(v-if="question_number == 8" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Je balance pas moi  
      router-link.reponse.reponse-8(v-if="question_number == 8" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") J’y gagne quoi ?
      router-link.reponse.reponse-8(v-if="question_number == 8" :to="{path: '/reponse/' + question_number}" @click.native="correctAnswer") Le corbeau

      router-link.reponse.reponse-9(v-if="question_number == 9" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Mere grand 
      router-link.reponse.reponse-9(v-if="question_number == 9" :to="{path: '/reponse/' + question_number}" @click.native="correctAnswer") Le loup garou
      router-link.reponse.reponse-9(v-if="question_number == 9" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Ta copine

      router-link.reponse.reponse-10(v-if="question_number == 10" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Les chats  
      router-link.reponse.reponse-10(v-if="question_number == 10" :to="{path: '/reponse/' + question_number}" @click.native="correctAnswer") Psychose
      router-link.reponse.reponse-10(v-if="question_number == 10" :to="{path: '/reponse/' + question_number}" @click.native="wrongAnswer") Un voisin Voyeur
</template>

<style lang="sass">
.question-container
  position: relative
  // background-color: blue
  padding: 2rem 0 2rem 0

.relative-container
  position: relative

.crack
  position: absolute

.crack1
  top: 33%
  left: 10%

.crack3
  top: 41%
  left: 8.75%

.crack4
  top: 6%
  left: 45%

.crack5
  top: 30%
  left: 25%

.crack2
  top: 35%
  left: 42%

//<REPONSE>//
.reponse
  font-size: 1rem
  font-family: "Montserrat-Bold"
  padding-bottom: 1vh
  display: inline-block
  text-align: center

  +tablet
    font-size: 1.25rem

.reponse-1
  color: #E9D4AE

.reponse-2
  color: #F0EDE6

.reponse-3
  color: #FFFFFF

.reponse-4
  color: #E7D95C

.reponse-5
  color: #DC2523

.reponse-6
  color: #FBD749

.reponse-7
  color: #738D39

.reponse-8
  color: #AEABD7

.reponse-9
  color: #FFFFFF

.reponse-10
  color: #F02403
//</REPONSE>//

.link-container
  flex-direction: column
  display: flex
  align-items: center
</style>

<script>
export default {
  name: "Question",
  props: ["question_number"],
  methods: {
    correctAnswer() {
      this.$store.dispatch("correctAnswer", this.question_number);
    },
    wrongAnswer() {
      this.$store.dispatch("wrongAnswer", this.question_number);
    }
  }
};
</script>
