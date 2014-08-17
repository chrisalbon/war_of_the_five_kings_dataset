# The Battles Of The War Of The Five Kings, A Dataset

This repo contains a dataset of the battles in the War of the Five Kings from George R.R. Martin's A Song Of Ice And Fire series.

This side project came out because I outside [my](http://chrisralbon.com) [my](https://github.com/chrisalbon) [regular](http://crisis.net) [projects](http://ushahidi.com) I have been looking for a small-n dataset to teach various aspects of data science. Datasets with "non-fiction" data are more interesting to me, but also come with the mess, complications, and grey-areas associated with the real world. On the other end of the spectrum, randomly generated datasets can make it more difficult to use as a teaching tool because it is often impossible to tell when an output (e.g. a visualization or analysis) "just looks wrong". So instead of making up a dataset from entirely from random-values, George R.R. Martin series gave me the source material to create a dataset that both fictional and with (for anyone that has read the series) built-in context.

## Codebook

This readme file acts as the codebook for the dataset.

### Variables:

- **name:** String variable. The name of the battle.
- **year:** Numeric variable. The year of the battle.
- **attacker_king:** Categorical. The attacker's king. A slash indicators that the king charges over the course of the war. For example, "Joffrey/Tommen Baratheon" is coded as such because one king follows the other in the Iron Throne.
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
