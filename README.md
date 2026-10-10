# skillyog-seals
Daily integrity seals for SkillYog test results

This repository holds one public code per day for SkillYog (skillyog.com) test results.

Each night, every result submitted or re-marked that day is combined into a single code using SHA-256, and each day's code is chained to the previous day's. The code is published here as one line: the date and the code.

No names, schools, marks or counts are published. A published code cannot be changed later without breaking the chain, so it lets a school or reviewer confirm that results were not altered after the day they were sealed.

Files: seals/YYYY-MM/YYYY-MM-DD.txt
