# pharma_research_model

### Contains the pkl file of the state dict for the model described in our associated publication. 

#### This model was created using our vulcan framework and the hyperparameters listed in the paper. 

#### The data scaler is a sklearn object https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html for which the variable ordering is     

```
var_ordering_scaling = ['insomnia_early_onset', 'hamd15', 'psychomotor_agitation', 
    'insomnia_late_night', 'suicidal_ideation_overall_recent', 'weight_loss_two_weeks', 
    'hamd14', 'guilt_thoughts_beliefs', 'appetite_decreased', 'insomnia_middle_night', 
    'feelings_of_worthlessness', 'hamd11', 'hamd17', 'somatic_gastro_intestinal', 'hamd10', 
    'hopeless_future', 'sociodem2', 'anxiety_mood', 'somatic_leaden_paralysis']
```

#### The equating object is a python dictionary that contains the equipercentile transformations needed as described in the associated publication.
