<template>
  <div class="px-[10vw] py-10">
    <div class="flex flex-col items-center">
      <p class="text-7xl pb-2">DevQuest</p>
      <br />
      <p class="text-xl">
        CS 426 Senior Project in Computer Science, Spring 2025, at UNR, CSE
        Department
      </p>
      <p class="text-xl">
        Team 35: Tyler Olson, Matt Stanley, and Jason Parmar
      </p>
      <p class="text-xl">Instructors: David Feil-Seifer and Sara Davis</p>
      <p class="text-xl">
        External Advisor: Eric Olson - Senior DevOps Engineer at Figure Markets
      </p>
    </div>
    <br />
    <div>
      <h2 class="text-3xl mb-6">Project Overview</h2>
      <div class="space-y-4">
        <p>
          DevQuest is an educational web application designed to teach fundamental
          Computer Science concepts through a gamified learning experience. The
          goal is to make learning Programming Basics, Data Structures, and
          Algorithms more engaging and accessible, especially for beginners.
          Inspired by platforms like Duolingo, our project incorporates
          interactive elements such as quizzes, coding challenges, and progress
          tracking to keep users motivated.
        </p>

        <p>
          It is designed for students, self-learners, and beginners who want to
          strengthen their understanding of Computer Science in a structured and
          interactive way. Many learners struggle with traditional, text-heavy
          materials, and this helps bridge this gap by making concepts more
          digestible through hands-on challenges and rewards.
        </p>
        <p>
          The app provides public value by making Computer Science education more
          accessible to those who may not have access to formal training. By
          offering a free or low-cost learning alternative, DevQuest aims to help
          more people develop valuable coding skills. It also keeps users engaged
          with a competitive yet friendly learning environment through
          leaderboards and progress tracking, encouraging long-term engagement.
        </p>

        <p>
          DevQuest includes an interactive glossary that allows users to quickly
          look up key Computer Science terms and concepts. The gamified learning
          system rewards users with points, streaks, and level-ups as they
          complete lessons and challenges. A global and friend-based leaderboard
          fosters motivation by allowing users to compare their progress with
          others. User progress, scores, and achievements are saved to ensure
          continuous learning. Hands-on coding challenges reinforce theoretical
          concepts, while secure user authentication provides a personalized
          experience.
        </p>

        <p>
          The backend is developed using Go for efficient server-side logic and
          API development. The frontend is built with Vue via Nuxt to create a
          dynamic and responsive user interface. Postgres is used as our database
          solution for storing user progress and other data. Additional tools are
          Docker for containerization and Tailwind for CSS styling.
        </p>
        <p>
          To ensure reliability, we undergo testing such as unit testing, integration
          testing, and load testing, to guarantee stability and smooth
          performance. Security measures include secure authentication, data
          encryption, input validation, and rate limiting.
        </p>
        <p>
          By integrating gamification, structured learning, and strong security
          measures, DevQuest aims to make Computer Science education more
          engaging, effective, and widely accessible.
        </p>
      </div>

      <section class="mt-12">
        <h2 class="text-3xl mb-6">Project Related Resources</h2>

        <div class="mb-8">
          <h3 class="text-2xl mb-4">Research Papers & Technical Reports</h3>
          <div class="space-y-4">
            <div>
              <a href="https://www.researchgate.net/publication/258697764_Gamification_in_Education_What_How_Why_Bother"
                class="text-blue-300 hover:text-blue-400"
                target="_blank"
                rel="noopener noreferrer">
                Gamification in Education: What, How, Why Bother?
              </a>
              <p class="mt-1">
                Research demonstrating gamification's potential to boost student engagement and motivation in educational settings, particularly when addressing challenges like dropout rates. Through analysis of gamification's core concepts, applications, and theoretical frameworks, evidence supports its value in educational design.
              </p>
            </div>
            <div>
              <a href="https://www.sciencedirect.com/science/article/abs/pii/S0191491X15300407"
                class="text-blue-300 hover:text-blue-400"
                target="_blank"
                rel="noopener noreferrer">
                Assessment and Student Success in Higher Education
              </a>
              <p class="mt-1">
                Research on the importance of feedback in higher education assessment, emphasizing timely, relevant, and context-appropriate feedback for enhancing student learning and classroom dynamics.
              </p>
            </div>
          </div>
        </div>

        <div class="mb-8">
          <h3 class="text-2xl mb-4">Related Websites & Learning Platforms</h3>
          <div class="space-y-4">
            <div>
              <a href="https://www.duolingo.com/"
                class="text-blue-300 hover:text-blue-400"
                target="_blank"
                rel="noopener noreferrer">
                Duolingo
              </a>
              <p class="mt-1">
                A model platform for gamified learning, demonstrating effective implementation of micro-lessons, reward systems, and progress monitoring features.
              </p>
            </div>
            <div>
              <a href="https://www.codecademy.com/"
                class="text-blue-300 hover:text-blue-400"
                target="_blank"
                rel="noopener noreferrer">
                Codecademy
              </a>
              <p class="mt-1">
                An interactive coding education platform featuring structured learning paths and achievement systems, serving as a model for engaging computer science education.
              </p>
            </div>
            <div>
              <a href="https://www.youtube.com/@freecodecamp"
                class="text-blue-300 hover:text-blue-400"
                target="_blank"
                rel="noopener noreferrer">
                freeCodeCamp (YouTube)
              </a>
              <p class="mt-1">
                Extensive collection of free, in-depth computer science tutorials and project-based learning resources, covering a wide range of programming topics.
              </p>
            </div>
          </div>
        </div>

        <div class="mb-8">
          <h3 class="text-2xl mb-4">Problem Domain Book</h3>
          <div class="space-y-4">
            <div>
              <p class="font-semibold text-blue-300">
                The Gamification of Learning and Instruction: Game-based Methods and Strategies for Training and Education (2012) by Karl M. Kapp
              </p>
              <p class="mt-1">
                This seminal work provides a comprehensive framework for implementing game mechanics in educational contexts. Kapp thoroughly examines how game elements like challenges, rewards, and engagement loops can enhance learning outcomes. The book's research-based approach to gamification directly influenced our project's design principles, particularly in how we structure our learning progression, reward systems, and user engagement features. Its insights on balancing entertainment with educational value helped shape DevQuest's approach to making computer science concepts both engaging and effectively learned.
              </p>
            </div>
          </div>
        </div>

        <div class="mb-8">
          <h3 class="text-2xl mb-4">News and Technology Updates</h3>
          <div class="space-y-4">
            <div>
              <a href="https://v2.nuxt.com/releases/"
                class="text-blue-300 hover:text-blue-400"
                target="_blank"
                rel="noopener noreferrer">
                Nuxt 3.9 Release
              </a>
              <p class="mt-1">
                Latest Nuxt update brings significant performance improvements and new features that enhance development workflow, which will benefit our frontend implementation.
              </p>
            </div>

            <div>
              <a href="https://go.dev/doc/go1.23"
                class="text-blue-300 hover:text-blue-400"
                target="_blank"
                rel="noopener noreferrer">
                Go 1.21 Release Overview
              </a>
              <p class="mt-1">
                Go's latest major release introduces built-in support for structured logging and improved performance, features we'll leverage in our backend development.
              </p>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script lang="ts" setup>
useHead({ title: "Home" });
</script>

<style>
body {
  @apply bg-gray-600 text-gray-50;
}
</style>
