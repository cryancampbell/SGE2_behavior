## SGE2_behavior
Code to calculate final behavioral metrics for SGE2 Phases 1 &amp; 2

This is final code to generate group-centered Agonisms Received Rate, Overall Grooming Rate, and Elo for SGE2 phases 1 & 2.
This code will output behavioral values for all animals, for all 4 experiments (SGE2p1 Environmental Challenge, SGE2p1 Single Cell, SGE2p1 Vaccine, SGE2p2 Vaccine)
It will also generate dataset-specific numbers to complete a clear methods section (behavior_methods_text.txt)

# Column descriptions
for:
object = sge.behave.summary.full
file = sge2Behavior_shortCols_phase<1/2>_adj<SingleCell/Vax/EnvChall>.txt

ID - Individual ID, two-letter code
phase.agg - Phase of SGEII Experiment
group.agg - Individual's Group
intro.no - Order of introduction from intro_all
elo.agg - final elo from intro_all
num.obs - Total number of 30 min. observational period that the animal was recorded in
ordinal.rank - rank from the elo in intro_all
agg.received - count of agonisms received
id.group - column of ID_group
eloID - Individual two-letter ID
calcElo - Elo calculated from specified subset of data (pre-sample collection)
groupEloStab - group stability of calcElo
elo.groom - Elo from intro_all
min - minutes of grooming total
min.give - minutes of grooming given
min.receive - minutes of grooming received
no.obs - Total number of 30 min. observational period that the animal was recorded in
group.groom - Individual's Group
phase.groom - Phase of SGEII Experiment
rawGroomRate - grooming minutes per hour; (groom.min/no.obs)*2
rawAggRecRate - aggression events received per hour; (agg.received.count/no.obs)*2
calcOrdRank - ordinal rank from calcElo (from specified subset of data, pre-sample collection)
groupcent_groom - within group centered grooming rate
groupcent_agRec - within group centered rate of agonisms received
groupcent_elo - within group cenetered Elo
group.gc - Individual's Group
adjDate - experiment that data was generated for
fractionKept - fraction of full phase's observations used, fraction of observations taken before this experiment
animalID - Full animal ID (R__##, e.g. RAi10 where two-letter is AI)
experimentDate - date of sampling for this animal