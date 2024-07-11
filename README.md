
# Report for Assignment 1 resit

## Project chosen

Name: <Trafilatura>

URL: <https://github.com/adbar/trafilatura>

Number of lines of code and the tool used to count it: 

26320

tool: Find and wc command unix:

find . -name '*.py' | xargs wc -l

Programming language: <Python>

## Coverage measurement with existing tool

Coverage Python tool was used:
Cmd used: "coverage run --branch spider_tests.py && coverage html"


### Individual tests

<The following is supposed to be repeated for each function (2 in total)>

<process_response>

<Show a patch (diff) or a link to a commit made in your forked repository that shows the new/enhanced tests for function 1>

<Provide a screenshot of the old coverage results for such function>

![Screenshot 2024-07-11 at 20 44 16](https://github.com/Pedro105/trafilatura/assets/41062943/556bfe58-2aeb-45f1-b964-fa1fdcc69677)

<Provide a screenshot of the new coverage results for such function>
    
![Screenshot 2024-07-11 at 20 45 27](https://github.com/Pedro105/trafilatura/assets/41062943/8ca7f25d-00fc-4515-8c7b-a1b4e4c662c6)

<State the coverage improvement with a number and elaborate on why the coverage is improved>

Coverage 78% -> 91%

<focused_crawler>

<Show a patch (diff) or a link to a commit made in your forked repository that shows the new/enhanced tests for function 1>

<Provide a screenshot of the old coverage results for such function>
    
![Screenshot 2024-07-11 at 20 44 26](https://github.com/Pedro105/trafilatura/assets/41062943/0139f71b-df18-42a5-a2f0-aff24f179ac8)

<Provide a screenshot of the new coverage results for such function>
    
![Screenshot 2024-07-11 at 20 45 14](https://github.com/Pedro105/trafilatura/assets/41062943/419444d2-c1e5-482d-b2f7-5ad252d4d349)

<State the coverage improvement with a number and elaborate on why the coverage is improved>

Coverage 70% -> 79%

### Overall

## Original Coverage

![Screenshot 2024-07-11 at 19 33 26](https://github.com/Pedro105/trafilatura/assets/41062943/984ed248-f257-478e-8464-94f0532ac76d)

## Coverage improvement

![Screenshot 2024-07-11 at 20 13 08](https://github.com/Pedro105/trafilatura/assets/41062943/bd5e48d2-ce20-4435-add1-703c165ee44e)


## Footnote:

I initially attempted to modify the process_links function but ran into issues and decided to switch to focused_crawler.
