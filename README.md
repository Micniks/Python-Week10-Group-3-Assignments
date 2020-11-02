# Gruppe 3 - Uptight Wealth
*Ikke vores valg af gruppenavn*

**Gruppemedlemmer:**
- Cahit
- Marcus
- Michael

# The Python Cult

<img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/bb485920-261e-46b9-896a-cb18fda5d929/dbvl0da-050b7754-242a-4a9f-adff-e4a4c8652fcd.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOiIsImlzcyI6InVybjphcHA6Iiwib2JqIjpbW3sicGF0aCI6IlwvZlwvYmI0ODU5MjAtMjYxZS00NmI5LTg5NmEtY2IxOGZkYTVkOTI5XC9kYnZsMGRhLTA1MGI3NzU0LTI0MmEtNGE5Zi1hZGZmLWU0YTRjODY1MmZjZC5wbmcifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6ZmlsZS5kb3dubG9hZCJdfQ.39OiImVLazb8JFOfhDJWFl2529SJ7obSvPHoSpKNka4" alt="Cult Symbol" width="200">

#### Assignment 1: Organize your cult
*This assignment is meant to make a setup for the two others below, and needs to be completed before the assignement 2 & 3*
1. Read in the random names in the file ***Random_Names.txt*** into a list ***cultist_names***.
2. Make a support method ***recruit_cultist***, that takes a string **name**, and returns a dict with *skills* as below, each assigned a random int between 0 and 5:
`
cultist = {'name': {'stealth': int, 'influence': int, 'endurance': int, 'lore': int, 'economic': int, 'strength': int, 'insanity': int}}
`
3. Run all names from ***cultist_names*** thought the ***recruit_cultist*** method, and gather all the results in a ***cult*** dict
4. Make the following dict ***cult_roles*** as below. Each value represents how importent a skill is for the given role:
```python
cult_roles {
'Priest': {'stealth': 0, 'influence': 3, 'endurance': 1, 'lore': 3, 'economic': 0, 'strength': 0, 'insanity': 5},
'Enforcer': {'stealth': 1, 'influence': 1, 'endurance': 3, 'lore': 0, 'economic': 0, 'strength': 4, 'insanity': 1},
'Assassin': {'stealth': 4, 'influence': -1, 'endurance': 2, 'lore': 1, 'economic': 0, 'strength': 2, 'insanity': 3},
'Recruiter': {'stealth': 1, 'influence': 4, 'endurance': 1, 'lore': 2, 'economic': 2, 'strength': 0, 'insanity': 4},
'Accountant': {'stealth': 0, 'influence': 0, 'endurance': 1, 'lore': 2, 'economic': 5, 'strength': 1, 'insanity': -1},
'Advisor': {'stealth': 0, 'influence': 2, 'endurance': 3, 'lore': 5, 'economic': 1, 'strength': 0, 'insanity': 2},
'Initiate': {'stealth': 1, 'influence': 1, 'endurance': 1, 'lore': 1, 'economic': 1, 'strength': 1, 'insanity': 1}
}
```
5. Make a method ***assign_cult_roles***, that takes the ***cult*** and ***cult_roles*** dicts, and returned the ***cult*** dict, where each name dict has gotten an attribute role. Each role should be assign on which of the roles have the highest 'score' when dotted between the name dict and the cult_roles.

![cultist](https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/be796ae1-a2db-40a4-ab06-6aa42a607e91/dd7vv03-f5d37c61-a181-4185-84b5-866857e0965b.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOiIsImlzcyI6InVybjphcHA6Iiwib2JqIjpbW3sicGF0aCI6IlwvZlwvYmU3OTZhZTEtYTJkYi00MGE0LWFiMDYtNmFhNDJhNjA3ZTkxXC9kZDd2djAzLWY1ZDM3YzYxLWExODEtNDE4NS04NGI1LTg2Njg1N2UwOTY1Yi5wbmcifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6ZmlsZS5kb3dubG9hZCJdfQ.R7fnou_nsvV9raJk_o1eyJ14ETdryFbAm8a4wLdUQ2M)

#### Assignment 2: Cult Recruitment Statistics
1. Save the data from the ***cult_statistics.csv*** file in a variable ***cult_data*** *(You can use panda here)*
2. Plot new recruits as a function to amount_spend.
3. Plot new recruits as a function to total_amount.
4. Make a model object from *klearn linear regression model* to use for the following assignments.
5. Predict new recuits if amount_spend doubles
6. Predict new recuits if total_amount decrease by 20%
7. Reverse the data, to predict how much amount_spend should be, to make new_recruits equal to 1000

![cult_gathering](https://thebingbutt.files.wordpress.com/2019/01/buttcultgathering.jpg)

#### Assignment 3: PENDING...
*Group has not fully understood Machine learning for Python, and need to research before posting a relevent assignment*

_______________________

Vi benytter datasættene: [Random Names](pending...) & [Cult Statistics](pending...)

Dette github repository er tilrettet opgavestillinger, så udspecifieret her: [Uge7 Opgave](https://docs.google.com/document/d/1ojSiBWwLo4-Rc7763vx6aVEYdNluATOMja9qqk4dodU/edit#) 