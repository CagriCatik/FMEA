# FMEA Handbook

This handbook is structured to guide you through the principles, processes, and practices of FMEA, providing both theoretical knowledge and practical activities to ensure a thorough understanding.

## Table of Contents

### 1. Understanding FMEA

- [Introduction](./chapter_1/1_introduction.md)
- [Defining Failure Mode and Effect Analysis (FMEA)](./chapter_1/2_defining_fmea.md)
- [Reasons and Timing for Using FMEA](./chapter_1/3_reasons_timing_fmea.md)
- [The History of FMEA](./chapter_1/4_history_fmea.md)
- [Types of FMEA](./chapter_1/5_types_fmea.md)
- [Overview of Process FMEA](./chapter_1/6_overview_process_fmea.md)
- [Activity: Understanding FMEA](./chapter_1/7_activity_understanding_fmea.md)
- [Activity Solution: Understanding FMEA](./chapter_1/8_activity_solution_understanding_fmea.md)

### 2. Stage 01: Identifying the Failure Mode and Specifying its Severity

- [Introduction](./chapter_2/introduction.md)
- [The Six Stages of FMEA](./chapter_2/six_stages_fmea.md)
- [Process FMEA: Top Section Overview](./chapter_2/top_section_overview.md)
- [Components of Stage 01: Part 01](./chapter_2/components_stage01_part01.md)
- [Components of Stage 01: Part 02](./chapter_2/components_stage01_part02.md)
- [Components of Stage 01: Part 03](./chapter_2/components_stage01_part03.md)
- [Activity: Stage 01](./chapter_2/activity_stage01.md)
- [Activity Solution: Stage 01](./chapter_2/activity_solution_stage01.md)

### 3. Stage 02: Specifying the Occurrence of Failure

- [Introduction](./chapter_3/introduction.md)
- [Identifying Potential Causes](./chapter_3/identifying_potential_causes.md)
- [Defining the Occurrence Rating](./chapter_3/defining_occurrence_rating.md)
- [Activity: Stage 02](./chapter_3/activity_stage02.md)
- [Activity Solution: Stage 02](./chapter_3/activity_solution_stage02.md)

### 4. Stage 03: Specifying the Detectability of Failure

- [Introduction](./chapter_4/introduction.md)
- [Current Process Controls Overview](./chapter_4/process_controls_overview.md)
- [Defining the Detectability Rating](./chapter_4/defining_detectability_rating.md)
- [Activity: Stage 03](./chapter_4/activity_stage03.md)
- [Activity Solution: Stage 03](./chapter_4/activity_solution_stage03.md)

### 5. Stage 04 and 05: Quantifying Risk and Correcting High-Risk Situations

- [Introduction](./chapter_5/introduction.md)
- [Explanation of RPN (Risk Priority Number)](./chapter_5/explanation_rpn.md)
- [Recommended Actions for Risk Mitigation](./chapter_5/risk_mitigation_actions.md)
- [Assigning Responsibility, Target Completion Dates, and Actions Taken](./chapter_5/assigning_responsibility.md)

### 6. Stage 06: Reevaluating the Risk and Visualizing FMEA Rankings

- [Introduction](./chapter_6/introduction.md)
- [Calculation of the Resulting RPN](./chapter_6/calculating_rpn.md)
- [Creating a Spider Chart for FMEA Visualization](./chapter_6/creating_spider_chart.md)

### 7. Steps to Construct an FMEA

- [Introduction](./chapter_7/introduction.md)
- [Detailed Steps to Construct an FMEA - Part 01](./chapter_7/steps_to_construct_fmea_part01.md)
- [Detailed Steps to Construct an FMEA - Part 02](./chapter_7/steps_to_construct_fmea_part02.md)

### 8. Benefits and Shortcomings of FMEA

- [Benefits of FMEA](./chapter_8/benefits_fmea.md)
- [Limitations and Challenges of FMEA](./chapter_8/limitations_challenges_fmea.md)

## About This Handbook

This handbook is intended for professionals, engineers, and students who are involved in quality management, product development, and risk assessment. The content is organized to build a foundational understanding of FMEA, followed by a detailed examination of its application stages, and concluding with a discussion of its benefits and limitations.

## How to Use This Handbook

Each chapter in this handbook provides both theoretical insights and practical exercises. You are encouraged to work through the activities to solidify your understanding of FMEA concepts. Solutions are provided to help you check your work and ensure you are on the right track.

## Cloning and Building the Handbook

To get started with this handbook locally, you can clone the repository and build it using `mdBook`. Follow the steps below:

### Prerequisites

- Ensure you have [Rust](https://www.rust-lang.org/tools/install) installed.
- Install `mdBook` by running the following command:

  ```bash
  cargo install mdbook
  ```

### Cloning the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/CagriCatik/FMEA
cd FMEA
```

### Building the Book

Once inside the project directory, you can build the book by running:

```bash
mdbook build
```

This will generate the static files for the book in the `book` directory.

### Serving the Book Locally

To view the book in your browser, you can serve it locally using:

```bash
mdbook serve --open
```

Open your browser and navigate to `http://localhost:3000` to view the book.
