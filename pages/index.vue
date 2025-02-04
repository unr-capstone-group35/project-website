<template>
  <div class="px-[10vw] py-10">
    <div class="flex flex-col items-center">
      <p class="text-7xl">DevQuest</p>
      <br />
      <p class="text-xl">
        CS 426 Senior Project in Computer Science, Spring 2025, at UNR, CSE
        Department
      </p>
      <p class="text-xl">
        Team 35: Tyler Olson, Matt Stanley, and Jason Parmar
      </p>
      <p class="text-xl">Instructors: David Feil-Seifer and Sara Davis</p>
      <p class="text-xl">External Advisor: Eric Olson</p>
    </div>
    <br />
    <div>
      <p class="">
        DevQuest is an educational web application designed to teach fundamental
        Computer Science concepts through a gamified learning experience. The
        goal is to make learning Programming Basics, Data Structures, and
        Algorithms more engaging and accessible, especially for beginners.
        Inspired by platforms like Duolingo, our project incorporates
        interactive elements such as quizzes, coding challenges, and progress
        tracking to keep users motivated. It is designed for students,
        self-learners, and beginners who want to strengthen their understanding
        of Computer Science in a structured and interactive way. Many learners
        struggle with traditional, text-heavy materials, and this helps bridge
        this gap by making concepts more digestible through hands-on challenges
        and rewards. The app provides public value by making Computer Science
        education more accessible to those who may not have access to formal
        training. By offering a free or low-cost learning alternative, DevQuest
        aims to help more people develop valuable coding skills. It also keeps
        users engaged with a competitive yet friendly learning environment
        through leaderboards and progress tracking, encouraging long-term
        engagement. DevQuest includes an interactive glossary that allows users
        to quickly look up key Computer Science terms and concepts. The gamified
        learning system rewards users with points, streaks, and level-ups as
        they complete lessons and challenges. A global and friend-based
        leaderboard fosters motivation by allowing users to compare their
        progress with others. User progress, scores, and achievements are saved
        to ensure continuous learning. Hands-on coding challenges reinforce
        theoretical concepts, while secure user authentication provides a
        personalized experience. The backend is developed using Go for efficient
        server-side logic and API development. The frontend is built with Vue
        via Nuxt to create a dynamic and responsive user interface. Postgres is
        used as our database solution for storing user progress and other data.
        Additional tools are Docker for containerization and Tailwind for CSS
        styling. To ensure reliability, we undergo testing such as unit testing,
        integration testing, and load testing, to guarantee stability and smooth
        performance. Security measures include secure authentication, data
        encryption, input validation, and rate limiting. By integrating
        gamification, structured learning, and strong security measures,
        DevQuest aims to make Computer Science education more engaging,
        effective, and widely accessible.
      </p>
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
