# The War Of The Five Kings, A Dataset

This repo contains a dataset of the battles in the War of the Five Kings from George R.R. Martin's A Song Of Ice And Fire series.

This small side project came about because I outside [of](http://chrisralbon.com) [my](https://github.com/chrisalbon) [regular](http://crisis.net) [projects](http://ushahidi.com) I have been looking for a small-n dataset to use as a data science teaching tool. While "non-fiction" datasets are, frankly, more interesting, they also come with the mess, complications, and grey-areas associated with the real world. On the other end of the spectrum, randomly generated datasets can be difficult to use as a teaching tool because their outputs (e.g. visualizations or analyses) are meaningless. So, instead of generating a dataset from random-values, the George R.R. Martin series provides ample source material to create a dataset that is both fictional and with (for anyone that has read the series) built-in context. Also, I had a few hours to kill in an airport.

[Here is an exploratory analysis of the dataset on nbviewer](http://nbviewer.ipython.org/github/chrisalbon/war_of_the_five_kings_dataset/blob/master/exploratory_analysis.ipynb)

## Codebook

This readme file acts as the codebook for the dataset.

### Level Of Observation:
- The battles of the War of the Five Kings

### Variables:

- **name:** String variable. The name of the battle.
- **year:** Numeric variable. The year of the battle.
- **battle_number:** Numeric variable. A unique ID number for the battle.
- **attacker_king:** Categorical. The attacker's king. A slash indicates that the king changes over the course of the war. For example, "Joffrey/Tommen Baratheon" is coded as such because one king follows the other in the Iron Throne.
- **defender_king:** Categorical variable. The defender's king.
- **attacker_1:** String variable. Major house attacking.
- **attacker_2:** String variable. Major house attacking.
- **attacker_3:** String variable. Major house attacking.
- **attacker_4:** String variable. Major house attacking.
- **defender_1:** String variable. Major house defending.
- **defender_2:** String variable. Major house defending.
- **defender_3:** String variable. Major house defending.
- **defender_4:** String variable. Major house defending.
- **attacker_outcome:** Categorical variable. The outcome from the perspective of the attacker. Categories: win, loss, draw.
- **battle_type:** Categorical variable. A classification of the battle's primary type. Categories:
    - pitched\_battle: Armies meet in a location and fight. This is also the baseline category.
    - ambush: A battle where stealth or subterfuge was the primary means of attack.
    - siege: A prolonged of a fortied position.
    - razing: An attack against an undefended position
- **major_death:** Binary variable. If there was a death of a major figure during the battle.
- **major_capture:** Binary variable. If there was the capture of the major figure during the battle.
- **attacker_size:** Numeric variable. The size of the attacker's force. No distinction is made between the types of soldiers such as cavalry and footmen.
- **defender_size:** Numeric variable. The size of the defenders's force. No distinction is made between the types of soldiers such as cavalry and footmen.
- **attacker_commander:** String variable. Major commanders of the attackers. Commander's names are included without honoric titles and commandders are seperated by commas.
- **defender_commander:** String variable. Major commanders of the defener. Commander's names are included without honoric titles and commandders are seperated by commas.
- **summer:** Binary variable. Was it summer?
- **location:** String variable. The location of the battle.
- **region:** Categorical variable. The region where the battle takes place. Categories: Beyond the Wall, The North, The Iron Islands, The Riverlands, The Vale of Arryn, The Westerlands, The Crownlands, The Reach, The Stormlands, Dorne
- **note:** String variable. Coding notes regarding individual observations.

### Source:

- [A Wiki of Fire and Ice's War Of The Five Kings](http://awoiaf.westeros.org/index.php/War_of_the_Five_Kings) page on the war and the pages of individual battles. Data collected August 17, 2014 at 4:30am-ish.


### Are you a huge ASOIAF fan?

Not really. I just love data - all data.


 [This data is mirrored and can be queried via API here](https://www.exversion.com/data/view/YVCREKZP14Y2XXC)
