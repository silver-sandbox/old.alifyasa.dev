<script setup lang="ts">
import Project from '../components/Project.vue'
</script>

<template>
  <main class="px-16 text-zinc-100 font-montserrat" aria-label="My Projects">
    <h1 class="text-5xl font-bold my-16">
      PROJECTS
    </h1>
    <div class="grid sm:grid-cols-1 lg:grid-cols-2 2xl:grid-cols-3 gap-2 my-16">
      <Project title_="Reddit Comment Archiver" link_="https://github.com">
        <p>
          A periodic archiving system to capture and store Reddit comments on a scheduled basis.
        </p>
        <p>
        Made using <b>Docker</b> and utilized <b>AWS</b> services, including <b>AWS SES</b> to send email notifications, <b>AWS Fargate</b> to run containerized app, and <b>AWS Lambda</b> to execute Fargate Tasks.
        </p>
      </Project>
      <Project title_="TCP Simulation" link_="https://github.com">
        <p>
        A TCP-like protocol implemented in <b>Python</b> on top of UDP with TCP principles such as congestion control, flow control, error detection, and correction mechanisms to ensure reliable delivery of data.
        </p>
      </Project>
      <Project title_="Dots and Boxes AI" link_="https://github.com">
        <p>
          AI agent for the classic game of Dots and Boxes, written in <b>Python</b>. 
        </p>
        <p>
        Implemented <i>Simulated Annealing</i> and <i>Minimax</i> algorithms to enable the agent to make intelligent moves during gameplay.
        </p>
      </Project>
      <Project title_="Network Traffic Visualizer" link_="https://github.com">
        <p>
        A network traffic visualizer using <b>Python</b> and <b>Bash</b> to capture network traffic data and <b>Matplotlib</b> to visualize it.
        </p>
      </Project>
    </div>
  </main>
</template>
