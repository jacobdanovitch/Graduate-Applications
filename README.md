# Fall 2020 Graduate Applications

Open-sourcing my graduate admissions package to hopefully help make the process a little bit less intimidating and opaque (but mostly for the latex template tbh).

## Quick Overview

* Accepted to 3/6 programs
  * All programs Canadian
  * All offers funded to varying degrees
    * I think UBC offered less than minimum wage lol
* Interviewed for UofT (MSc), MILA 3x (different professors)
* COVID made this process super fun right there at the end
* Accepted offer from Professor Reihaneh Rabbany at MILA

## Statement of Purpose

95% of the content for each SOP was the same; I setup a template to change the name of the school in the first paragraph as well as insert a personalized conclusion as the final paragraph. To change the school:

```shell
FLDR=SOP/templates/$SCHOOL
mkdir FLDR; touch $FLDR/info.tex $FLDR/professors.tex
```

Then change [`SOP/main.tex:53`](https://github.com/jacobdanovitch/Graduate-Applications/blob/49ad756605a24d5ac8714a5fc110be8de2090eae/SOP/main.tex#L53) to whatever you used as $SCHOOL.

I've included content for the school I chose, MILA, which includes content for the aforementioned files as well as the compiled PDF output.

## Admission Results

|     School    |   Applied  | Official Notification | Admitted |
|:-------------:|:----------:|:---------------------:|:--------:|
|   UofT (MSc)  | 12/09/2019 |       03/31/2020      |     ❌    |
|  UofT (MSASc) | 12/09/2019 |       03/30/2020      |     ❌    |
|      UBC      | 12/15/2019 |       04/28/2020      |     ✅    |
| **MILA (McGill)** | 12/28/2019 |       03/26/2020      |     ✅    |
|    Carleton   | 01/06/2020 |       01/31/2020      |     ✅    |
|      SFU      | 01/05/2020 |       05/12/2020      |     ❌    |

## Interviews

## Referees
