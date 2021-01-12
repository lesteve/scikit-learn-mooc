<!-- 
- part: The predictive modeling pipeline
  chapters:
  - file: predictive_modeling_pipeline/predictive_modeling_module_intro
  - file: predictive_modeling_pipeline/01_tabular_data_exploration_index
    sections:
      - file: python_scripts/01_tabular_data_exploration
      - file: predictive_modeling_pipeline/01_tabular_data_exploration_quiz
  - file: predictive_modeling_pipeline/02_numerical_pipeline_index
    sections:
      - file: python_scripts/02_numerical_pipeline_introduction
      - file: python_scripts/02_numerical_pipeline_hands_on
      - file: python_scripts/02_numerical_pipeline_ex_01
      - file: python_scripts/02_numerical_pipeline_sol_01
      - file: python_scripts/02_numerical_pipeline_scaling
      - file: predictive_modeling_pipeline/02_numerical_pipeline_quiz
  - file: predictive_modeling_pipeline/03_categorical_pipeline_index
    sections:
      - file: python_scripts/03_categorical_pipeline
      - file: python_scripts/03_categorical_pipeline_ex_01
      - file: python_scripts/03_categorical_pipeline_sol_01
      - file: python_scripts/03_categorical_pipeline_column_transformer
      - file: python_scripts/03_categorical_pipeline_ex_02
      - file: python_scripts/03_categorical_pipeline_sol_02
      - file: predictive_modeling_pipeline/03_categorical_pipeline_quiz
  - file: predictive_modeling_pipeline/predictive_modeling_module_take_away
  - file: final_evaluation/predictive_modeling_pipeline_questions

-->
<!-- part -->

# The predictive modeling pipeline

<!-- section level: need to parse the file before the section to find the title -->
## Tabular data exploration

<!-- file level: need to parse the file to find the title -->
- [First look at our dataset](01_tabular_data_exploration.ipynb)

## Fitting a scikit-learn model on numerical data

- [First model with scikit-learn](02_numerical_pipeline_introduction.ipynb)
-  [Working with numerical data](02_numerical_pipeline_hands_on.ipynb)
- [Exercise 01](02_numerical_pipeline_ex_01.ipynb)
- [Preprocessing for numerical features](python_scripts/02_numerical_pipeline_scaling.ipynb)

## Handling categorical data

- [Encoding of categorical variables](03_categorical_pipeline.ipynb)
- [Exercise 01](03_categorical_pipeline_ex_01.ipynb)
- [Using numerical and categorical variables together](03_categorical_pipeline_column_transformer.ipynb)
- [Exercise 02](03_categorical_pipeline_ex_02.ipynb)

# Hyperparameters tuning

## Manual tuning

<!-- 
- part: Hyperparameters tuning
  chapters:
    - file: tuning/parameter_tuning_module_intro
    - file: python_scripts/parameter_tuning_ex_01
    - file: python_scripts/parameter_tuning_sol_01
    - file: tuning/parameter_tuning_manual_index
      sections:
        - file: python_scripts/parameter_tuning_manual
        - file: python_scripts/parameter_tuning_ex_02
        - file: python_scripts/parameter_tuning_sol_02
    - file: tuning/parameter_tuning_automated_index
      sections:
        - file: python_scripts/parameter_tuning_automated
        - file: python_scripts/parameter_tuning_ex_03
        - file: python_scripts/parameter_tuning_sol_03
    - file: tuning/parameter_tuning_quiz
    - file: tuning/parameter_tuning_module_take_away
-->

- [Set and get hyperparameters in scikit-learn](python_scripts/parameter_tuning_automated.ipynb) 
- [Exercise 01](python_scripts/parameter_tuning_ex_02.ipynb)

## Automated tuning

- [Automated hyperparameters tuning in scikit-learn](python_scripts/parameter_tuning_automated.ipynb)
- [Exercise 02](python_scripts/parameter_tuning_ex_03.ipynb)

<!-- link to quizzes or forget about them ??? -->

<!-- It feels like there is going to be some editorial decision to keep some
parts or not so maybe a script that generates the full index and then you
remove lines you don't want manually? -->
