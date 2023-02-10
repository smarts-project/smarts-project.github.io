---
permalink: /archive/2022_nips_driving_smarts/
title: "NeurIPS 2022 Driving SMARTS Competition"
toc: true
---


## End Notice

The 2022 NeurIPS Driving SMARTS Competition has now ended!

Many thanks to all the organizers and participants who contributed to the competition.

The original competition notice can be seen at [here](#the-competition)

## Results

The competition objective is to train a single policy capable of controlling single-agent or multi-agent to complete different driving tasks in various scenarios.

#### Track 1

Task: Any method may be used to develop the policy.

| Rank        | Prize   | Team        | Solution    | Presentation |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| 1st         | 6000 USD | tjudrllab-fanta  | [fanta-code](https://github.com/superCat-star/fanta-code)     | [tjudrllab_fanta_driving_smarts](assets/docs/neurips_2022_smarts_method-TJUDRLLAB_Fanta.pdf)     |
| 2nd         | 4000 USD | VCR         | [SMARTS_VCR](https://github.com/yuant95/SMARTS_VCR/tree/ddc23f73556eb946f02e0699cc0fa2294a0ffc38)     | [vcr_driving_smarts](assets/docs/team_VCRs_approach_to_neurips_driving_smarts_competition.pdf)     |
| 3rd         | 2000 USD | AID         | [Predictive-Decision](https://github.com/MCZhi/Predictive-Decision)     | [aid_driving_smarts](assets/docs/aid_driving_smarts.pdf)     |

Congratulations to the Track 1 winners!

#### Track 2

Task: An offline learning method using offline datasets must be used to develop the policy.

| Rank        | Prize   | Team        | Solution    | Presentation |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| 1st         | 6000 USD | tjudrllab-fanta  | [fanta-code](https://github.com/superCat-star/fanta-code)     | [tjudrllab_fanta_driving_smarts](assets/docs/neurips_2022_smarts_method-TJUDRLLAB_Fanta.pdf)     |
| 2nd         | 4000 USD | VCR         | [SMARTS_VCR](https://github.com/yuant95/SMARTS_VCR/tree/ddc23f73556eb946f02e0699cc0fa2294a0ffc38)     | [vcr_driving_smarts](assets/docs/team_VCRs_approach_to_neurips_driving_smarts_competition.pdf)     |
| 3rd         | 2000 USD | AID         | [Predictive-Decision](https://github.com/MCZhi/Predictive-Decision)     | [aid_driving_smarts](assets/docs/aid_driving_smarts.pdf)     |


Congratulations to the Track 2 winners!

#### Bonus Awards

| Category        | Prize   | Team        |
| ----------- | ----------- | ----------- |
| Most Innovative         | 1000 USD | AID  |
| Participation (Random selection)   | 1000 USD | tjudrllab-mb  |

Congratulations to AID for being unanimously voted by the organizing team as having the most innovative solution!


## The Competition

Autonomous driving (AD) is the next frontier of artificial intelligence and machine learning. Intending to further research in AD, we invite you to participate in an autonomous driving competition organised by NSERC Canadian Robotics Network (NCRN) and Canadian academic collaborators.


### Codalab Site 

[2022 Neurips Driving SMARTS Competition](https://codalab.lisn.upsaclay.fr/competitions/6618)

### Tasks and evaluation
This competition seeks to advance autonomous driving by developing agents that can drive as quickly and safely as possible from the start to destination amid background traffic. Data for the competition consists of large-scale naturalistic driving data replayed within [SMARTS](https://github.com/huawei-noah/SMARTS/tree/comp-1) simulation environment. The following typical driving scenarios are tested: cruising, overtaking, merging, left turns at unsignalized intersections and being cut off by another vehicle. These scenarios are mined from the naturalistic data, manipulated and replayed in SMARTS. For some scenarios, interactive background vehicles are added in SMARTS.

Agents will be ranked according to metrics on safety and comfort (smoothness and safe driving), task completion (% of completed scenarios), traffic rule violation, and completion time.

### Competition tracks
There are two tracks in the competition.

**Track 1**: The participants may use *any* method and training data to develop their solutions. 

**Track 2**: The participants are only allowed to train their methods on the *offline datasets*.

Winners in each track will receive cash prizes and will get a chance to present their innovative solutions during the virtual ceremony.

[Return to top](#the-competition)

### Competition timeline
The NeurIPS 2022 Driving SMARTS competition is a programming competition organised by NCRN and academic collaborators from Canadian universities.

* Aug. 1, 2022: competition opens.
* Nov. 8, 2022: competition closes at 11:59pm Pacific Time.
* Nov. 10, 2022: contestants will be asked to submit their training code and models for evaluation for Track2
* Nov. 12, 2022: Track1 winners will be announced. Track2 submission closes.
* Nov. 15, 2022: Track2 winning teams announced.

[Return to top](#the-competition)

### Prizes
Top participants in each track will receive the following prizes:
- **Gold** US$6000
- **Silver** US$4000
- **Bronze** US$2000

Additional prizes:
- US$1000 for the **most innovative** approach out of top-6 entries in both tracks
- US$1000 given to one of the valid submissions not in top-3 positions in either track

[Return to top](#the-competition)

### General Rules

- Participants can be a single entrant or part of a team;
- Participants must be registered for the competition prior to submitting an entry;
- Participants must be solely responsible for creating the submission (receiving supervision or advice from supervisors or colleagues is permitted);
- Participants must be able to share their training and inference code and trained models with the organizers;
- For the participants or a team to be eligible for receiving awards, each member must satisfy the following conditions:
  - be at least 18 years old or age of majority in place of residence;
  - not be an organizer of this competition or a family member of a competition organizer;
- Any submissions entered after the competition closes will be automatically disqualified. 

[Return to top](#the-competition)

#### How to enter
- The individual participant or, if a team is entering, a team representative, must register with the Organiser through the ["2022 Neurips Driving SMARTS Competition" site](https://codalab.lisn.upsaclay.fr/competitions/6618).
- The participants will be provided login details to CodaLab to submit a competition entry;
- Starter kit and necessary documentation will be available upon registration;
- The entry sumitted by the participant will consist of the pretrained model and inference code. Select participants who opted to compete in track 2 will be requested to submit their training code.
- Participants may submit up to 3 entries to the competition.

[Return to top](#the-competition)

### Submission site
The competition is run from the following site: [Driving SMARTS Competition submission](https://codalab.lisn.upsaclay.fr/competitions/6618)

### How winners are determined
- Submissions for Track 1 will be automatically evaluated on a test set and the results will be posted on the public leaderboard hosted on CodaLab.
- Top-6 finalists in Track 1 that use offline methods will be invited to submit their training and inference code. The organizers will train and evaluate the models on the withheld dataset. 
- Winners of Track 2 will be determined based on the performance of the models trained by the Organizer.
- The organizers will work with the participants who selected Track 2 to run their training code, participants may be asked to provide additional documentation to facilitate this process.

[Return to top](#the-competition)

### FAQ
Official rule clarifications will be posted here.

[Return to top](#the-competition)

### Competition Organizing Committee
- **Amir Rasouli**
  - Senior Staff Engineer, Huawei Noah's Ark Lab
- **Randy Goebel**
  - Professor, University of Alberta
- **Adam Scibior**
  - CTO and co-founder, Inverted AI
- **Matthew E. Taylor**
  - Associate Professor, University of Alberta
- **Iuliia Kotseruba**
  - PhD Candidate, York University
- **Tianpei Yang**
  - Postdoctoral Researcher, University of Alberta
- **Soheil Alizadeh**
  - Research Engineer, Huawei Noah's Ark Lab
- **Montgomery Alban**
  - Software Engineer, Huawei Noah's Ark Lab
- **Florian Shkurti**
  - Asisstant Professor, University of Toronto
- **Yuzheng Zhuang**
  - Senior Research Scientist, Huawei Noah's Ark Lab
- **Kasra Rezaee**
  - Staff Engineer, Huawei Noah's Ark Lab  
- **Xinyu Wang**
  - ADS Planning and Control Chief Architect, Huawei IAS BU
- **Weinan Zhang**
  - Associate Processor, Shanghai Jiao Tong University
- **Xi Chen**
  - Senior Principal Engineer, Huawei Noah's Ark Lab & Adjunct Professor, McGill University 
#### Advisers
- **Animesh Garg**
  - Assistant Professor, University of Toronto
- **David Meger**
  - Assistant Professor, McGill University
- **Jun Luo**
  - Distinguished Researcher, Huawei Noah's Ark Lab
- **Liam Paull**
  - Assistant Professor, University of Montreal 

[Return to top](#the-competition)

### Contact Us
Organizers can be reached at [**smarts4ad@gmail.com**](mailto:smarts4ad@gmail.com).

[Return to top](#the-competition)

### Organizers

{:style="text-align:center"}
![University of Alberta](https://www.ualberta.ca/_assets/images/ua-logo-green.svg){:width="196" height="73"}
![University of Toronto](https://user-images.githubusercontent.com/69439799/196953728-61672f42-99f8-4555-bb79-576e04d0dcdf.png)
![York University](https://user-images.githubusercontent.com/69439799/196953742-7ec4d140-d99b-48da-ad26-2e632c49ce6a.png)  

{:style="text-align:center"}
![Universite de Montreal](https://user-images.githubusercontent.com/69439799/196953954-609896af-d05d-4801-bdb6-91bfa3898290.png)
![McGill University](https://user-images.githubusercontent.com/69439799/196954083-c4b2cccf-d131-471b-8aa1-4acfc63ceb29.png)  

{:style="text-align:center"}
![NCRN RCRC](https://user-images.githubusercontent.com/69439799/196953417-d39ba2b1-eff1-443b-90ca-5d8657749dc1.png){:width="120" height="120"}

### Sponsors

{:style="text-align:center"}
![Huawei](https://www-file.huawei.com/-/media/corporate/images/home/logo/huawei_logo.png)  

{:style="text-align:center"}
![Noah's Ark](https://user-images.githubusercontent.com/69439799/196953928-7e9ac318-4206-47e2-98b2-5dd398fb3a64.png){:width="120" height="120"}

[View more details](http://noahlab.com.hk/#/home)

[Return to top](#the-competition)
