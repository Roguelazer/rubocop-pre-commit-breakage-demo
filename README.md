This is a demo application showing that rubocop is broken with pre-commit.

Reproduction steps:

 1. Install `pre-commit` 3.7.1
 2. Clone this repository (`git clone git@github.com:Roguelazer/rubocop-pre-commit-breakage-demo.git && cd rubocop-pre-commit-breakage-demo`)
 3. Configure pre-commit hooks (`pre-commit install`)
 4. Run pre-commit (`pre-commit run --all`)
