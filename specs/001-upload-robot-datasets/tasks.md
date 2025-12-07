# Tasks: Docusaurus Book Development

**Input**: Design documents from `/specs/001-upload-robot-datasets/`
**Prerequisites**: plan.md

## Phase 1: Docusaurus Setup

**Purpose**: Project initialization and basic structure for the Docusaurus site.

- [x] T001 Install Node.js (LTS) and yarn on the development machine.
- [x] T002 Run `npx create-docusaurus@latest robotics-docs classic` in the project root to scaffold the site.
- [x] T003 Navigate into the newly created `robotics-docs` directory.
- [x] T004 Run `yarn install` to install all necessary dependencies.
- [x] T005 Run `yarn start` to launch the local development server and confirm the default site is running.
- [x] T006 [P] Modify `docusaurus.config.js` to set the `title`, `tagline`, `url`, and `baseUrl`.
- [x] T007 [P] Create a `favicon.ico` file and place it in the `static/img` directory.
- [x] T008 [P] Configure the theme in `docusaurus.config.js`, including the navbar and footer.

**Checkpoint**: A basic, running Docusaurus site is configured with the book's branding.

---

## Phase 2: Chapter 1 Development (Core Concepts)

**Purpose**: Create the structure and content for the first chapter of the book.

- [x] T009 Create the directory `robotics-docs/docs/01-core-concepts`.
- [x] T010 [P] Create the lesson file `robotics-docs/docs/01-core-concepts/01-intro-to-physical-ai.md`.
- [x] T011 [P] Create the lesson file `robotics-docs/docs/01-core-concepts/02-basics-of-humanoid-robotics.md`.
- [x] T012 [P] Create the lesson file `robotics-docs/docs/01-core-concepts/03-setting-up-the-dev-environment.md`.
- [x] T013 Create the category metadata file `robotics-docs/docs/01-core-concepts/_category_.json` with the label "Core Concepts".
- [x] T014 Update the `sidebars.js` file in the `robotics-docs` directory to include the `01-core-concepts` directory, making the chapter visible in the navigation.
- [x] T015 Write the full content for the "Introduction to Physical AI" lesson in `robotics-docs/docs/01-core-concepts/01-intro-to-physical-ai.md`.
- [x] T016 Write the full content for the "Basics of Humanoid Robotics" lesson in `robotics-docs/docs/01-core-concepts/02-basics-of-humanoid-robotics.md`.
- [x] T017 Write the full content for the "Setting up the Development Environment" lesson in `robotics-docs/docs/01-core-concepts/03-setting-up-the-dev-environment.md`.

**Checkpoint**: The "Core Concepts" chapter is complete with three lessons, and is visible on the Docusaurus site.

---

## Phase 3: Core Concepts (Continued)

**Purpose**: Complete the remaining lessons in the Core Concepts phase.

- [x] T018 Create the lesson file `robotics-docs/docs/01-core-concepts/04-hello-robot-project.md` with placeholder content.
- [ ] T019 Write the full content for the "Hello, Robot!" lesson.

---

## Phase 4: Beginner Projects

**Purpose**: Create the structure and content for the Beginner Projects phase.

- [x] T020 Create the directory `robotics-docs/docs/02-beginner-projects`.
- [x] T021 Create the category metadata file `robotics-docs/docs/02-beginner-projects/_category_.json` with the label "Beginner Projects".
- [x] T022 [P] Create the lesson file `robotics-docs/docs/02-beginner-projects/01-sensor-data-acquisition.md` with placeholder content.
- [x] T023 [P] Create the lesson file `robotics-docs/docs/02-beginner-projects/02-basic-locomotion.md` with placeholder content.
- [x] T024 [P] Create the lesson file `robotics-docs/docs/02-beginner-projects/03-simple-object-manipulation.md` with placeholder content.
- [x] T025 Write the full content for "Sensor data acquisition and processing".
- [x] T026 Write the full content for "Basic locomotion".
- [x] T027 Write the full content for "Simple object manipulation".
- [x] T028 Update `sidebars.js` to include the `02-beginner-projects` directory.

---

## Phase 5: Intermediate Projects

**Purpose**: Create the structure and content for the Intermediate Projects phase.

- [x] T029 Create the directory `robotics-docs/docs/03-intermediate-projects`.
- [x] T030 Create the category metadata file `robotics-docs/docs/03-intermediate-projects/_category_.json` with the label "Intermediate Projects".
- [x] T031 [P] Create the lesson file `robotics-docs/docs/03-intermediate-projects/01-intro-to-computer-vision.md` with placeholder content.
- [x] T032 [P] Create the lesson file `robotics-docs/docs/03-intermediate-projects/02-autonomous-navigation.md` with placeholder content.
- [x] T033 [P] Create the lesson file `robotics-docs/docs/03-intermediate-projects/03-advanced-locomotion.md` with placeholder content.
- [x] T034 Write the full content for "Introduction to computer vision for robotics".
- [x] T035 Write the full content for "Autonomous navigation and obstacle avoidance".
- [x] T036 Write the full content for "Advanced locomotion and dynamic balancing".
- [x] T037 Update `sidebars.js` to include the `03-intermediate-projects` directory.

---

## Dependencies & Execution Order

- **Phase 1 (Docusaurus Setup)** must be completed before Phase 2.
- Within Phase 2, tasks T009-T014 should be completed before T015-T017.
- Content writing tasks (T015, T016, T017) can be done in parallel.
- Phases should be completed sequentially (Phase 1 -> Phase 2 -> Phase 3 -> Phase 4 -> Phase 5).