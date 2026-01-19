Examples for UQ in Python to demonstrate CI capabilities of EESSI

Code is derived from https://github.com/kjetilly/GeiloWinterSchoolUQ
(Copyright (c) 2026 Kjetil Olsen Lye)

- Fork this repo https://github.com/trz42/PythonUQ
- In your fork adjust the file `.github/workflows/test_python_uq.yaml`
    - Replace `MODULE1`, `MODULE2` and `MODULE3` in the `test_python_uq.yaml` with actual module names that are needed to run the code `uq-in-python.py`.
    - Hints:
        - Determine modules that provide the software you need (python, numpy and matplotlib) by running commands like `module spider python` or `module spider numpy`.
        - You may need to run `module spider ...` several times refining `...` to determine what module you need to load. Follow the information provided as output of `module spider ...`.
        - Replace one `MODULE1/2/3`, then commit & push the changes to your fork.
        - Observe results of the workflow run (check Actions tab). The workflow succeeds if all modules that are needed were loaded. Otherwise there will be some error. Try to fix that. 
- Question: What are limitations running with GitHub Actions?
