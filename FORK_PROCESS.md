# LEAN Fork Process

This document outlines the process used to fork the QuantConnect LEAN repository into our LeanForge-LEAN repository.

## Steps Taken

1. Created a new empty GitHub repository named `LeanForge-LEAN`
2. Forked the official QuantConnect/Lean repository to our personal GitHub account
3. Created a README.md file to initialize our LeanForge-LEAN repository
4. Created this document to track the forking process

## Next Steps

1. Audit the codebase to identify all QuantConnect cloud dependencies
2. Create a mapping document that shows cloud components versus their local replacements
3. Begin the process of removing cloud dependencies
4. Set up CI/CD for this repository
5. Document all changes made

## Repository Details

- Original Repository: [QuantConnect/Lean](https://github.com/QuantConnect/Lean)
- Forked Repository: [Steve-ender/Lean](https://github.com/Steve-ender/Lean)
- Target Repository: [Steve-ender/LeanForge-LEAN](https://github.com/Steve-ender/LeanForge-LEAN)

## Import Details

The code from the forked repository will be imported to this repository using Git commands, preserving the commit history where appropriate while removing any unnecessary components.