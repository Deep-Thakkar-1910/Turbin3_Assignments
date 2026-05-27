# Turbin3 Builder Cohort - Assignment Submission

Welcome to my Turbin3 Builder's Cohort repository.
This is my primary workspace for cohort submissions, where each assignment lives in its own repository and is linked here as a Git submodule.

## About This Repository

- Program: `Turbin3 Builder's Cohort`
- Purpose: Track and submit weekly cohort work
- Structure: One main repository + assignment repositories as submodules
- Current milestone: `Week 1`

## Repository Structure

This repo acts as a submission hub:

```text
.
├── README.md
├── .gitmodules
└── assignment0/   # Git submodule
└── assignment1/   # Git submodule
└── assignment1_tui_version/   # Git submodule
└── assignment2/   # Git submodule
└── assignment3_vault/   # Git submodule
└── assignment3_escrow/   # Git submodule
└── assignment4_amm/   # Git submodule
```

### Assignment Overview

| #       | Assignment                                                                                                  | Description                                                                                                            |
| ------- | ----------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| 0       | [Turbine_assignment0](https://github.com/Deep-Thakkar-1910/Turbine_assignment0)                             | Initialization and setup                                                                                               |
| 1       | [Turbine_assignment1](https://github.com/Deep-Thakkar-1910/Turbine_assignment1)                             | Guessing game from the Rust Book                                                                                       |
| 1 (TUI) | [Turbine_assignment1_TUI_Version](https://github.com/Deep-Thakkar-1910/Turbine_assignment1_TUI_version.git) | TUI version of the guessing game (extra)                                                                               |
| 2       | [Turbine_assignment2](https://github.com/Deep-Thakkar-1910/Turbine_assignment2)                             | SPL token creation with metadata, minting & transferring. NFT using Metaplex Core asset accounts with a royalty plugin |
| 3       | [Turbine_assignment3_vault](https://github.com/Deep-Thakkar-1910/Turbine_assignment3_vault)                 | Anchor program implementing a Vault with expiry                                                                        |
| 3       | [Turbine_assignment3_escrow](https://github.com/Deep-Thakkar-1910/Turbine_assignment3_escrow)               | Anchor program implementing an Escrow                                                                                  |
| 4       | [Turbine_assignment4_amm](https://github.com/Deep-Thakkar-1910/Turbine_assignment4_amm)                     | Anchor program implementing a constant product AMM                                                                     |

### Configured Submodules

- `assignment0` -> [Turbine_assignment0](https://github.com/Deep-Thakkar-1910/Turbine_assignment0)
- `assignment1` -> [Turbine_assignment1](https://github.com/Deep-Thakkar-1910/Turbine_assignment1)
- `assignment1_tui_version` -> [Turbine_assignment1_TUI_Version](https://github.com/Deep-Thakkar-1910/Turbine_assignment1_TUI_version.git)
- `assignment2` -> [Turbine_assignment2](https://github.com/Deep-Thakkar-1910/Turbine_assignment2)
- `assignment3_vault` -> [Turbine_assignment3_vault](https://github.com/Deep-Thakkar-1910/Turbine_assignment3_vault)
- `assignment3_escrow` -> [Turbine_assignment3_escrow](https://github.com/Deep-Thakkar-1910/Turbine_assignment3_escrow)
- `assignment4_amm` -> [Turbine_assignment4_amm](https://github.com/Deep-Thakkar-1910/Turbine_assignment4_amm)

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
