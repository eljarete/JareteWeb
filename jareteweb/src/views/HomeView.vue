<template>
  <div class="home">
    <img
      alt="Vue logo"
      src="../assets/FotoJarete.jpg"
      width="200"
      height="240"
    />
    <HeaderDescription
      header="Jared Arroyo Martín"
      description="My name is Jared Arroyo, industrial engineer specialized in systems
      electronics and industry 4.0. Let me introduce myself in three different
      dimensions that I hope will help you take a picture of me.
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
      solid work teams.
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
      term.
      About my interests: I feel passionate about new technologies, sports, and
      engineering. I consider myself a responsible, diplomatic, proactive, and
      flexible person. I have good analytic skills, a sensitive empathy for
      social relationships and remarkable habits documenting everything I learn
      to keep it in mind. Currently I am looking for new professional challenges
      oriented to develop my IIoT/Industry 4.0 knowledge using the latest
      technologies."
    />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HeaderDescription from "@/components/HeaderDescription.vue"; // @ is an alias to /src

@Component({
  components: {
    HeaderDescription,
  },
})
export default class HomeView extends Vue {}
</script>
