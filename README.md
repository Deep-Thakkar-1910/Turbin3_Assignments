# Turbin3 Builder Cohort - Week 0 Submission

Welcome to my Turbin3 Builder's Cohort repository.
This is my primary workspace for cohort submissions, where each assignment lives in its own repository and is linked here as a Git submodule.

## About This Repository

- Program: `Turbin3 Builder's Cohort`
- Purpose: Track and submit weekly cohort work
- Structure: One main repository + assignment repositories as submodules
- Current milestone: `Week 0`

## Repository Structure

This repo acts as a submission hub:

```text
.
├── README.md
├── .gitmodules
└── assignment0/   # Git submodule
└── assignment1/   # Git submodule
```

### Configured Submodules

- `assignment0` -> [Turbine_assignment0](https://github.com/Deep-Thakkar-1910/Turbine_assignment0)
- `assignment0` -> [Turbine_assignment1](https://github.com/Deep-Thakkar-1910/Turbine_assignment1)

## Working With Submodules

Clone with submodules:

```bash
git clone --recurse-submodules https://github.com/Deep-Thakkar-1910/Turbin3_Assignments.git
```

If already cloned, initialize and update:

```bash
git submodule update --init --recursive
```

Pull latest changes in all submodules:

```bash
git submodule update --remote --merge
```

## Notes

This README will evolve as new assignments and submodules are added each week.
