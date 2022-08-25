<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p align="left">
      My name is Jared Arroyo, industrial engineer specialized in systems
      electronics and industry 4.0. Let me introduce myself in three different
      dimensions that I hope will help you take a picture of me.<br />
      About my professional experience: during the last four years I have been
      working in the systems department of an industrial manufacturer company in
      the environmental sector. Here I develop hardware/software projects on the
      administration and industrial areas as: ERP integrations to comply with
      the company workflows, providing data mining from industrial sensors,
      design of business analytics to report production KPIs and sales results
      as well as the maintenance of IT systems and devices. Before this
      position, I have been dedicated for three years to cloud applications
      consultancy where my main functions were the advice, implantation,
      maintenance, and improvement of software projects for customers. In my
      professional experience I could highlight my role as functional-technical
      leader, a good management of the knowledge base trending to flatten
      learning curves in new knowledges and a positive contribution to build
      solid work teams.<br />
      About my academic training: during my industrial engineering (EQF 7)
      training I collaborated in multiple investigation projects on systems
      electronics and automation: development and implantation of a traffic
      monitoring network, programming of distributed automation systems,
      construction of robots based in Arduino/Raspberry boards, PLC and
      industrial robots programming. On 2020 I decided to complement my classic
      industry knowledge studding a master on Industry 4.0 where I learnt new
      essential concepts for current IIoT technologies. Lately, since I
      understood the importance of connected systems on the master, I decided to
      learn about Linux systems and DevOps methodologies to have a better
      understanding of embedded systems. Five years ago, I also began studding a
      Master on Business Administration from which I keep learning on long
      term.<br />
      About my interests: I feel passionate about new technologies, sports, and
      engineering. I consider myself a responsible, diplomatic, proactive, and
      flexible person. I have good analytic skills, a sensitive empathy for
      social relationships and remarkable habits documenting everything I learn
      to keep it in mind. Currently I am looking for new professional challenges
      oriented to develop my IIoT/Industry 4.0 knowledge using the latest
      technologies.<br />
    </p>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class HelloWorld extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
