<script setup lang="ts">
import Project from '../components/Project.vue'
</script>

<template>
  <main class="px-16 text-zinc-100 font-montserrat" aria-label="My Projects">
    <h1 class="text-5xl font-bold my-16">
      PROJECTS
    </h1>
    <div class="grid sm:grid-cols-1 lg:grid-cols-2 2xl:grid-cols-3 gap-2 my-16">
      <Project title_="Reddit Comment Archiver" link_="https://github.com/genshin-subreddit-analytics">
        <p>
          A periodic archiving system to capture and store Reddit comments on a scheduled basis.
        </p>
        <p>
        Made using <b>Docker</b> and utilized <b>AWS</b> services, including <b>AWS SES</b> to send email notifications, <b>AWS Fargate</b> to run containerized app, and <b>AWS Lambda</b> to execute Fargate Tasks.
        </p>
      </Project>
      <Project title_="PeduliPantaiku" link_="https://gitlab.informatika.org/TubesForLyfe/if2250-2022-k03-04-pedulipantaiku">
        <p>
        A Desktop application made using <b>Python</b> to create a forum for sharing beach cleaning activities with CI/CD pipeline and <b>Docker</b>-ized database for testing.
        </p>
      </Project>
      <Project title_="Farm Simulation RPG" link_="https://github.com/ZianTsabit/TubesLogkom">
        <p>
          An RPG about Farming. Made in <b>GNU Prolog</b>.
        </p>
        <p>
          <i>"Claire is a girl who has just been scammed by a client who just disappeared without paying for the project she worked so hard to build. Apart from being a victim of fraud, Claire is also in debt of 20,000 gold which needs to be repaid within 1 year. Therefore, Claire decided to return to her hometown and continue her grandfather's farming business to be able to continue living and pay off her debts."</i>
        </p>
      </Project>
      <Project title_="TCP Simulation" link_="https://github.com/Sister19/jarkom-jaringansakitkepala">
        <p>
        A TCP-like protocol implemented in <b>Python</b> on top of UDP with TCP principles such as congestion control, flow control, error detection, and correction mechanisms to ensure reliable delivery of data.
        </p>
      </Project>
      <Project title_="Dots and Boxes AI" link_="https://github.com/malifpy/Dots-and-Boxes">
        <p>
          AI agent for the classic game of Dots and Boxes, written in <b>Python</b>. 
        </p>
        <p>
        Implemented <i>Simulated Annealing</i> and <i>Minimax</i> algorithms to enable the agent to make intelligent moves during gameplay.
        </p>
      </Project>
      <Project title_="DNA Pattern Matcher" link_="https://github.com/malifpy/Tubes3_13520135">
        <p>
          A Web Application for DNA Pattern Matching made using <b>Go</b> backend and <b>PostgreSQL</b> database. It uses <i>Boyer-Moore</i> and <i>Knuth-Morris-Pratt</i> algorithm to compare DNA string with database.
        </p>
      </Project>
      <Project title_="Python Syntax Checker" link_="https://github.com/lizardyy/TBuFalO">
        <p>
          Python Syntax Checker made using Context-Free Grammar and CYK algorithm.
        </p>
      </Project>
      <Project title_="Network Traffic Visualizer" link_="https://github.com/malifpy/network-stat-log">
        <p>
        A network traffic visualizer using <b>Python</b> and <b>Bash</b> to capture network traffic data and <b>Matplotlib</b> to visualize it.
        </p>
      </Project>
      <Project title_="Wikipedia Speedrun Solver" link_="https://github.com/malifpy/wikipedia-speedrun-solver">
        <p>
          Solves <a href="https://wikispeedruns.com/" target="_blank" class="underline">Wikipedia Speedrun</a> using <i>Branch and Bound</i> algorithm.
        </p>
      </Project>
      <Project title_="Minimum Vertex Cover Finder" link_="https://github.com/malifpy/wikipedia-speedrun-solver">
        <p>
          Calculate the Minimum <a href="https://en.wikipedia.org/wiki/Vertex_cover" target="_blank" class="underline">Vertex Cover</a> using <i>Divide and Conquer</i> algorithm.
        </p>
      </Project>
    </div>
  </main>
</template>
