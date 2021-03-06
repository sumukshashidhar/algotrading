# File Structure

```
+-- .gitignore (files to be ignored by git)
+-- LICENSE (GPLv3 License)
+-- README.md (README file)
+-- docs (documentation)
|   +-- _config.yml (github pages configuration)
|   +-- ACTIVE.md (list of active projects)
|   +-- CONTRIBUTING.md (contribution guidelines)
|   +-- CONVENTION.md (project conventions)
|   +-- INDEX.md (gh pages homepage)
|   +-- RUN.md (installation/running instructions)
|   +-- STRUCTURE.md (project structure)
|   +-- TASKS.md (list of pending tasks)
+-- samples (various samples)
|   +-- data (different data samples)
|       +-- daily.csv (sample of long term daily data outputs)
|       +-- websocket.csv (sample of websocket data output)
|       +-- analysed.csv (sample of analysed data output)
+-- src (root of our codebase)
|   +-- interface (code to link with the broker. python) 
|   +-- backtesting (code to run backtests for specified datasets. java)
|   +-- sentiment_analysis (code to analyse news and social media. python)
|   +-- streamer (code to stream down data from websocket api. python)
```