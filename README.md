# AI Journey

A public log of my 10-week journey from Power Systems to AI Agents.

## About Me
M.Tech scholar with a background in Power Systems, learning AI Engineering step by step.

## My Goal
Learn Python, Git, machine learning, GenAI and AI agents, and build practical projects. My final project is the **Grid Insight Agent**, an AI agent that answers questions about power system data.

## Daily Study Time
About 55 minutes every day.

## 10-Week Roadmap
- [ ] Week 1: Git, GitHub and a Python refresh
- [ ] Week 2: Python for data (Pandas)
- [ ] Week 3: Machine learning basics
- [ ] Week 4: LLMs and your first API call
- [ ] Week 5: AI agents (Hugging Face course, Unit 1)
- [ ] Week 6: Agent frameworks (Unit 2)
- [ ] Week 7: Agentic RAG (Unit 3)
- [ ] Week 8: Final challenge (Unit 4)
- [ ] Week 9: Project, Grid Insight Agent
- [ ] Week 10: Polish, publish and apply

## Daily Log

Tick each box when done and add a note. Days run from Day 1 to Day 70.

## Week 1: Git, GitHub and a Python refresh

### Day 1: Create your GitHub home
- [x] Created my GitHub account
- [x] Created this repository
- [x] Learned the basics of Git, GitHub and commits

**What I learned**
- **Git:** a version-control system that tracks changes in files and manages different versions of a project.
- **GitHub:** an online platform where developers store Git repositories, share projects and collaborate.
- **Commit:** a recorded snapshot of changes, saved with a message describing what changed.

### Day 2: Bring GitHub to your computer
- [ ] Install Git and VS Code
- [ ] Check `git --version` and `python --version`
- [ ] Clone `ai-journey` and open it in VS Code

**Notes:** 

### Day 3: The save-and-upload loop
- [ ] Finish the Git video
- [ ] Do add, commit, push 3 times

**Notes:** 

### Day 4: Python refresh, part 1
- [ ] Kaggle Python, lessons 1-3

**Notes:** 

### Day 5: Python refresh, part 2
- [ ] Kaggle Python, lessons 4-7

**Notes:** 

### Day 6: Mini project: power calculator
- [ ] Write `week-01/power_calc.py`
- [ ] Commit and push

**Notes:** 

### Day 7: Review and catch up
- [ ] Finish leftovers and claim Kaggle Python certificate
- [ ] Write Week 1 summary

**Notes:** 

## Week 2: Python for data (Pandas)

### Day 8: Creating, reading and writing data
- [ ] Kaggle Pandas, lesson 1
- [ ] Build a tiny DataFrame of 5 substations

**Notes:** 

### Day 9: Selecting rows and columns
- [ ] Kaggle Pandas, lesson 2
- [ ] Filter substations above 50 MW

**Notes:** 

### Day 10: Summary functions and maps
- [ ] Kaggle Pandas, lesson 3
- [ ] Add a kW column

**Notes:** 

### Day 11: Grouping and sorting
- [ ] Kaggle Pandas, lesson 4
- [ ] Total load per region, sorted

**Notes:** 

### Day 12: Messy data
- [ ] Kaggle Pandas, lessons 5-6 (lesson 6 by Day 14 at the latest)

**Notes:** 

### Day 13: Mini project: load analysis
- [ ] `week-02/load_analysis.py` prints peak, peak hour, average and load factor
- [ ] Commit and push

**Notes:** 

### Day 14: Review
- [ ] Claim Kaggle Pandas certificate
- [ ] Write Week 2 summary

**Notes:** 

## Week 3: Machine learning basics

### Day 15: How models work
- [ ] Kaggle Intro to ML, lesson 1
- [ ] Draw a 3-question decision tree on paper

**Notes:** 

### Day 16: Looking at data first
- [ ] Kaggle Intro to ML, lesson 2

**Notes:** 

### Day 17: Your first model
- [ ] Kaggle Intro to ML, lesson 3

**Notes:** 

### Day 18: Is the model any good?
- [ ] Kaggle Intro to ML, lesson 4 (MAE)

**Notes:** 

### Day 19: Overfitting and random forests
- [ ] Kaggle Intro to ML, lessons 5-6

**Notes:** 

### Day 20: Mini project: load predictor
- [ ] Random Forest predicts load from hour and temperature
- [ ] Print the MAE
- [ ] Push to `week-03/`

**Notes:** 

### Day 21: Review
- [ ] Claim Kaggle Intro to ML certificate
- [ ] Add a mini glossary (feature, target, training, validation, overfitting)
- [ ] Write Week 3 summary

**Notes:** 

## Week 4: LLMs and your first API call

### Day 22: What is an LLM?
- [ ] Start Claude 101 or a beginner LLM course
- [ ] Define token, prompt, context window, hallucination

**Notes:** 

### Day 23: Prompting, part 1: be clear
- [ ] Save 5 power-topic prompts in `week-04/prompts.md`

**Notes:** 

### Day 24: Prompting, part 2: steps and JSON
- [ ] Get clean JSON back from a prompt

**Notes:** 

### Day 25: Get an API key safely
- [ ] Create a free API key
- [ ] Store it in an environment variable
- [ ] Add `.gitignore` with `.env`
- [ ] First API call prints a reply

**Notes:** 

### Day 26: A tiny chatbot
- [ ] Chat loop that remembers history in a list

**Notes:** 

### Day 27: Mini project: fault explainer
- [ ] Returns JSON with `likely_causes` and `checks`
- [ ] Commit and push

**Notes:** 

### Day 28: Review
- [ ] Check the repo has no API key
- [ ] Claim Claude 101 certificate
- [ ] Write Week 4 summary

**Notes:** 

## Week 5: AI agents (Hugging Face course, Unit 1)

### Day 29: Unit 0: welcome
- [ ] Create Hugging Face account
- [ ] Join Discord and verify account
- [ ] Read the syllabus and note certificate requirements

**Notes:** 

### Day 30: What is an agent?
- [ ] Start Unit 1, first chapter
- [ ] Write one chatbot example and one agent example

**Notes:** 

### Day 31: LLMs and messages
- [ ] Understand messages and the system message

**Notes:** 

### Day 32: Tools
- [ ] Write `add(a, b)` with a clear docstring

**Notes:** 

### Day 33: The Think-Act-Observe loop
- [ ] Sketch the loop and save it in `week-05/`

**Notes:** 

### Day 34: Hands-on: your first agent
- [ ] Build the first agent
- [ ] Take the Unit 1 quiz

**Notes:** 

### Day 35: Review
- [ ] Write: what an agent is, in my own words
- [ ] Write Week 5 summary

**Notes:** 

## Week 6: Agent frameworks (Unit 2)

### Day 36: Why frameworks?
- [ ] List 3 things I would write myself without a framework

**Notes:** 

### Day 37: smolagents, part 1
- [ ] Unit 2.1, first half

**Notes:** 

### Day 38: smolagents, part 2
- [ ] Hands-on: run an agent with a built-in tool

**Notes:** 

### Day 39: Your first custom power tool
- [ ] Capacitor sizing tool for power factor correction
- [ ] Agent returns about 211 kVAR for 500 kW, 0.8 to 0.95 pf

**Notes:** 

### Day 40: LlamaIndex, skim
- [ ] Unit 2.2, one line on when to use it

**Notes:** 

### Day 41: LangGraph, skim
- [ ] Unit 2.3, one line on when to use it

**Notes:** 

### Day 42: Review
- [ ] Framework comparison table
- [ ] Write Week 6 summary

**Notes:** 

## Week 7: Agentic RAG (Unit 3)

### Day 43: What is RAG?
- [ ] Read the Unit 3 introduction
- [ ] Explain RAG with the open-book idea

**Notes:** 

### Day 44: How the lookup works
- [ ] Define chunk and embedding in one line each

**Notes:** 

### Day 45: Hands-on, part 1
- [ ] Get the Unit 3 RAG example running

**Notes:** 

### Day 46: Use-case assignment, start
- [ ] Choose an assignment and build the first half

**Notes:** 

### Day 47: Use-case assignment, finish
- [ ] Finish and submit the assignment

**Notes:** 

### Day 48: Try your own documents
- [ ] Ask 5 questions on 1-2 public power-sector documents
- [ ] Check answers against the source

**Notes:** 

### Day 49: Review
- [ ] Note 2 wrong answers and why
- [ ] Write Week 7 summary

**Notes:** 

## Week 8: Final challenge (Unit 4)

### Day 50: Understand the challenge
- [ ] Read Unit 4
- [ ] Write a 5-line summary

**Notes:** 

### Day 51: Set up
- [ ] Duplicate the template Space
- [ ] Add token via Space secrets
- [ ] Run it once unchanged

**Notes:** 

### Day 52: Give your agent tools
- [ ] Add web search, calculator, file reading
- [ ] Test each tool alone

**Notes:** 

### Day 53: Test on practice questions
- [ ] Run sample questions and list failures

**Notes:** 

### Day 54: Fix failures
- [ ] Fix the top 2 failures

**Notes:** 

### Day 55: Submit
- [ ] Submit and check the score

**Notes:** 

### Day 56: Claim your certificate
- [ ] Score above the bar and certificate claimed
- [ ] Add certificate to LinkedIn
- [ ] Write Week 8 summary

**Notes:** 

## Week 9: Project, Grid Insight Agent

### Day 57: Plan on paper
- [ ] Problem, data and 5 example questions in the project README
- [ ] Architecture box diagram

**Notes:** 

### Day 58: Data
- [ ] Create or collect the load CSV
- [ ] Clean it with Pandas

**Notes:** 

### Day 59: Tools
- [ ] `peak_load()`, `load_factor()`, `pf_correction_kvar()`, `find_anomalies()` all tested

**Notes:** 

### Day 60: Build the agent
- [ ] Connect tools to a smolagents agent
- [ ] Answers at least 3 of 5 questions correctly

**Notes:** 

### Day 61: Add documents
- [ ] RAG over 1-2 public documents
- [ ] Agent names its source

**Notes:** 

### Day 62: Test and record failures
- [ ] 10-question results table in the README

**Notes:** 

### Day 63: Fix and review
- [ ] Fix the top 3 failures
- [ ] Write Week 9 summary

**Notes:** 

## Week 10: Polish, publish and apply

### Day 64: Simple interface and live demo
- [ ] Gradio or Streamlit app
- [ ] Deployed on a Hugging Face Space

**Notes:** 

### Day 65: A professional README
- [ ] Problem, screenshot, diagram, how to run, limits

**Notes:** 

### Day 66: Profiles
- [ ] GitHub bio and pinned repos
- [ ] LinkedIn headline and certificates

**Notes:** 

### Day 67: Tell the story
- [ ] Publish a LinkedIn post about the project

**Notes:** 

### Day 68: Find targets
- [ ] List of 20 targets
- [ ] Notes on 3 job descriptions

**Notes:** 

### Day 69: Practice and apply
- [ ] Practice a 2-minute project explanation
- [ ] Apply or message 3-5 roles

**Notes:** 

### Day 70: Review and next 3 months
- [ ] Write Week 10 summary
- [ ] Pick next steps

**Notes:** 

## Repo Structure
- `week-01/` to `week-10/`: weekly practice files
- `projects/`: bigger projects, including the Grid Insight Agent
