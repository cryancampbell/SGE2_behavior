## SGE2_behavior
Code to calculate final behavioral metrics for SGE2 Phases 1 &amp; 2

This is final code to generate group-centered Agonisms Received Rate, Overall Grooming Rate, and Elo for SGE2 phases 1 & 2.
This code will output behavioral values for all animals, for all 4 experiments (SGE2p1 Environmental Challenge, SGE2p1 Single Cell, SGE2p1 Vaccine, SGE2p2 Vaccine)
It will also generate dataset-specific numbers to complete a clear methods section (behavior_methods_text.txt)

# Column descriptions
for:
object = sge.behave.summary.full
file = sge2Behavior_shortCols_phase<1/2>_adj<SingleCell/Vax/EnvChall>.txt

<p>ID - Individual ID, two-letter code<br>
phase.agg - Phase of SGEII Experiment<br>
group.agg - Individual's Group<br>
intro.no - Order of introduction from intro_all<br>
elo.agg - final elo from intro_all<br>
num.obs - Total number of 30 min. observational period that the animal was recorded in<br>
ordinal.rank - rank from the elo in intro_all<br>
agg.received - count of agonisms received<br>
id.group - column of ID_group<br>
eloID - Individual two-letter ID<br>
calcElo - Elo calculated from specified subset of data (pre-sample collection)<br>
groupEloStab - group stability of calcElo<br>
elo.groom - Elo from intro_all<br>
min - minutes of grooming total<br>
min.give - minutes of grooming given<br>
min.receive - minutes of grooming received<br>
no.obs - Total number of 30 min. observational period that the animal was recorded in<br>
group.groom - Individual's Group<br>
phase.groom - Phase of SGEII Experiment<br>
rawGroomRate - grooming minutes per hour; (groom.min/no.obs)*2<br>
rawAggRecRate - aggression events received per hour; (agg.received.count/no.obs)*2<br>
calcOrdRank - ordinal rank from calcElo (from specified subset of data, pre-sample collection)<br>
groupcent_groom - within group centered grooming rate<br>
groupcent_agRec - within group centered rate of agonisms received<br>
groupcent_elo - within group cenetered Elo<br>
group.gc - Individual's Group<br>
adjDate - experiment that data was generated for<br>
fractionKept - fraction of full phase's observations used, fraction of observations taken before this experiment<br>
animalID - Full animal ID (R__##, e.g. RAi10 where two-letter is AI)<br>
experimentDate - date of sampling for this animal<br>