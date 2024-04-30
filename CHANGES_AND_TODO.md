1. added new folder to data/synonyms + needed subfolders (still empty)
2. file added to conf/config_synonyms.yaml --> instead of config_default
3. file added to conf/train/data/synonyms.yaml --> instead of toy
4. file added to conf/train/config/splade_synonyms.yaml --> instead of splade_toy
5. modified splade/train.py --> added line 104,105,106 so it adds the new config files
6. modified conf/CONFIG_CHOICE.py --> changed CONFIG_NAME from config_default to config_synonyms

--------------------------------------how to continue-------------------------------------------

7. how to give the data
8. validation sets in conf/train/data/synonyms
9. preprocessing data
10. running splade/train.py, if there are errors debug until it works
11. use the new trained model in the notebook.