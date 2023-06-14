## Published work
#### Journal Articles
- __2022__
- Lam, K. H., Twose, J., Lissenberg-Witte, B., Licitra, G., Meijer, K., Uitdehaag, B., De Groot, V., Killestein, J. (2022). The use of smartphone keystroke dynamics to passively monitor upper limb and cognitive function in multiple sclerosis: a longitudinal analysis (In Press)

    - [https://www.jmir.org/author/submission/37614](https://www.jmir.org/author/submission/37614)

- Lam, K. H., Twose, J., McConchie, H., Licitra, G., Meijer, K., de Ruiter, L., ... & Killestein, J. (2022). Smartphone‐derived keystroke dynamics are sensitive to relevant changes in multiple sclerosis. _European journal of neurology, 29_(2), 522-534.

    - [https://onlinelibrary.wiley.com/doi/pdfdirect/10.1111/ene.15162](https://onlinelibrary.wiley.com/doi/pdfdirect/10.1111/ene.15162)

- __2021__
- Lam, K. H., Meijer, K. A., Loonstra, F. C., Coerver, E. M. E., Twose, J., Redeman, E., ... & Killestein, J. (2021). Real-world keystroke dynamics are a potentially valid biomarker for clinical disability in multiple sclerosis. _Multiple Sclerosis Journal, 27_(9), 1421-1431.

    - [https://journals.sagepub.com/doi/pdf/10.1177/1352458520968797](https://journals.sagepub.com/doi/pdf/10.1177/1352458520968797)

- __2020__
- Twose, J., Licitra, G., McConchie, H., Lam, K. H., & Killestein, J. (2020). Early-warning signals for disease activity in patients diagnosed with multiple sclerosis based on keystroke dynamics. _Chaos (Woodbury, NY), 30_(11), 113133.

    - [https://aip.scitation.org/doi/abs/10.1063/5.0022031](https://aip.scitation.org/doi/abs/10.1063/5.0022031)
    - [https://jameshtwose.github.io/EWS-supplemental-material/](https://jameshtwose.github.io/EWS-supplemental-material/)

#### Posters/ Abstracts
- __2021__
- Lam, K., Twose, J., Licitra, G., Meijer, K., Uitdehaag, B., De Groot, V., Killestein, J. (2021). Passively acquired smartphone keystroke dynamics are associated with clinical outcomes in multiple sclerosis: a longitudinal analysis (P302). _ECTRIMS 2021 - ePoster_

    - [https://journals.sagepub.com/doi/full/10.1177/13524585211044667](https://journals.sagepub.com/doi/full/10.1177/13524585211044667)

- __2020__
- Lam, K., Twose, J., McConchie, H., Licitra, G., Moraal, B., Barkhof, F., Uitdehaag, B., De Groot, V., Killestein, J. (2020). Smartphone keystroke dynamics are sensitive to changes in disease activity and clinical disability measures in multiple sclerosis. _ECTRIMS 2020_

    - [https://cslide.ctimeetingtech.com/msdc2020/attendee/person/1681](https://cslide.ctimeetingtech.com/msdc2020/attendee/person/1681)


## Projects/ Analyses at Neurocast
#### Innovation Options
- Using Linear Mixed Models to predict outcomes → look for changes using sum of dynamic complexity and cumulative complexity peaks ([_Twose et al, 2020_](https://jameshtwose.github.io/EWS-supplemental-material/))
- Recurrence Network Transitivity
    - Using multiple Recurrence Networks over a sliding window → from each network calculate the transitivity coefficient ([_Marwan & Kurths, 2015_](https://arxiv.org/pdf/1507.03778.pdf)) → compare the peaks in this coefficient with changes in outcome measure 
- Network approaches
    - ML-VAR and uSEM networks ([_Boorsboom et al., 2021_](https://eiko-fried.com/wp-content/uploads/Primer_s43586-021-00055-w_1629381676_1.pdf), [_Yang et al., 2018_](https://www.hindawi.com/journals/complexity/2018/5094179/))
- Optimal control theory
    - Coupled nonlinear difference equations to model outcomes (e.g. [_Schöller et al., 2018_](https://link.springer.com/article/10.1007/s11571-018-9488-y))
- Subtype and Stage Inference (SuStaIn)
    - Using SuStaIn to identify MS subtypes in keystroke data ([_Young et al., 2018_](https://www.nature.com/articles/s41467-018-05892-0), [_Aksman et al., 2021_](https://www.sciencedirect.com/science/article/pii/S2352711021001096))

#### Applications/ packages
- Created a sample size calculation web application called __*NeuroShiny*__ using __R Shiny__ and deployed it using __github actions__, __docker__ and __AWS ECR, ECS, fargate__
- Created a python package to help aid all internal analyses called __*neuropy*__. This included unit tests (pytest), Continuous Integration and Continuous Delivery (CICD) via github actions and was fully documented (sphinx) with complimentary scripts to show the intended use of all of the functions.
- Created a private pypi server to host internal python packages

#### Projects
- Amsterdam University medical center
    - longitudinal analysis using Linear Mixed Models to predict MS related outcome with keystroke composite scores ([_Lam et al., 2022_](https://www.jmir.org/author/submission/37614))
    - responsiveness analysis using receiver operating characteristic (ROC) analysis ([_Lam et al., 2022_](https://onlinelibrary.wiley.com/doi/pdfdirect/10.1111/ene.15162))
    - cross sectional analysis using correlations, t-tests, intra class correlations and bland-altman plots ([_Lam et al., 2021_](https://journals.sagepub.com/doi/pdf/10.1177/1352458520968797))
    - nonlinear time series analysis using dynamic complexity ([_Twose et al., 2020_](https://aip.scitation.org/doi/full/10.1063/5.0022031))
    - hierarchical machine learning analyses to predict MS outcomes (e.g. [_Hajjem, Bellavance and Larocque, 2014_](https://www.tandfonline.com/doi/abs/10.1080/00949655.2012.741599))

- Fatigue questionnaire validation using confirmatory factor analysis
- Writing a github wiki to explain data science methodology at Neurocast

## Personal Projects
- __2022__

- Landing page of analyses for the Citizen Shield project (Python, Jupyter, HTML, CSS)
    - [https://github.com/Citizen-Shield/multi-method-protective-behaviour](https://github.com/Citizen-Shield/multi-method-protective-behaviour)
    - [https://citizen-shield.github.io/multi-method-protective-behaviour/](https://citizen-shield.github.io/multi-method-protective-behaviour/)

- A fully functioning frontend for a food tracking application (React, Javascript, HTML, CSS)
    - [https://github.com/jameshtwose/jmstracker-frontend](https://github.com/jameshtwose/jmstracker-frontend)
    - [https://trckr.jms.rocks](https://trckr.jms.rocks)

- A fully functioning API backend for a food tracking application (Python - FastAPI, deta, Postgresql)
    - [https://github.com/jameshtwose/jmstracker-backend](https://github.com/jameshtwose/jmstracker-backend)
    - [https://4qcow4.deta.dev/docs](https://4qcow4.deta.dev/docs)

- A website showing latest data science work and portfolio (HTML, CSS, Javascript)
    - [https://github.com/jameshtwose/services.jms.rocks](https://github.com/jameshtwose/services.jms.rocks)
    - [https://services.jms.rocks](https://services.jms.rocks)

- A general Data Science repository (Python, R, Jupyter, HTML)
    - [https://github.com/jameshtwose/Data-Science](https://github.com/jameshtwose/Data-Science)
    - [https://jameshtwose.github.io/Data-Science/](https://jameshtwose.github.io/Data-Science/)

- A fully functioning chatbot (Pytorch, Flask, Microsoft Azure)
    - [https://github.com/jameshtwose/dumb_friend](https://github.com/jameshtwose/dumb_friend)

- Stand alone health app (Python - FastAPI, deta, nosql)
    - [https://github.com/jameshtwose/health_deta](https://github.com/jameshtwose/health_deta)
    - [https://jameshtwose.github.io/health_deta/](https://jameshtwose.github.io/health_deta/)
    - [https://2q6e55.deta.dev/docs](https://2q6e55.deta.dev/docs)

- Learning jQuery (Javascript)
    - [https://github.com/jameshtwose/learning_jquery](https://github.com/jameshtwose/learning_jquery)
    - [https://jameshtwose.github.io/learning_jquery/](https://jameshtwose.github.io/learning_jquery/)

- Vitarenal - suggested analyses (Python)
    - [https://github.com/jameshtwose/vitarenal-DS](https://github.com/jameshtwose/vitarenal-DS)
    - [https://jameshtwose.github.io/vitarenal-DS/](https://jameshtwose.github.io/vitarenal-DS/)

- Simple Surf Conditions Dashboard (HTML, CSS)
    - [https://github.com/jameshtwose/surf-dashboard](https://github.com/jameshtwose/surf-dashboard)
    - [https://jameshtwose.github.io/surf-dashboard/](https://jameshtwose.github.io/surf-dashboard/)

- Example Deliverables Documentation (Python, Github Actions)
    - [https://github.com/jameshtwose/example_deliverables](https://github.com/jameshtwose/example_deliverables)
    - [https://jameshtwose.github.io/example_deliverables/](https://jameshtwose.github.io/example_deliverables/)

- Todos App (Python - FastAPI, PostgreSQL)
    - [https://github.com/jameshtwose/todos-app](https://github.com/jameshtwose/todos-app)
    - [https://tp03k7.deta.dev](https://tp03k7.deta.dev)

- Sample Size Calculation Dashboard - __jmspwr__ (R - Shiny, Docker, Github Actions)
    - [https://github.com/jameshtwose/jmspwr](https://github.com/jameshtwose/jmspwr)
    - [https://itsamejms.shinyapps.io/jmspwr/](https://itsamejms.shinyapps.io/jmspwr/)

- Personal Python Package - __jmspack__ (Python)
- With unit tests, CICD, documentation showing examples and docstrings
    - [https://github.com/jameshtwose/jmspack](https://github.com/jameshtwose/jmspack)
    - Documentation: [https://docs.jms.rocks](https://docs.jms.rocks)

- Price Forecasting of Raw Materials (Python)
    - [https://github.com/jameshtwose/mike_jms_collabs](https://github.com/jameshtwose/mike_jms_collabs)
    - [https://jameshtwose.github.io/mike_jms_collabs/](https://jameshtwose.github.io/mike_jms_collabs/)

- Mobility Dashboard using Apple data (Python - dash, plotly)
    - [https://github.com/jameshtwose/apple-mobility-dash](https://github.com/jameshtwose/apple-mobility-dash)

- Generative music, and audio analysis (Python - librosa, music21)
    - [https://github.com/jameshtwose/musiplay](https://github.com/jameshtwose/musiplay)

- Sudoku Solver App (Javascript)
    - [https://github.com/jameshtwose/sudoku_solver](https://github.com/jameshtwose/sudoku_solver)

- Vanilla Documentation (Python, HTML, Github Actions)
    - [https://github.com/jameshtwose/vanilla_documentation](https://github.com/jameshtwose/vanilla_documentation)
    - [https://jameshtwose.github.io/vanilla_documentation/](https://jameshtwose.github.io/vanilla_documentation/)

- Learning Sphinx Documentation (Python, Github Actions)
    - [https://github.com/jameshtwose/learning_sphinx_documentation](https://github.com/jameshtwose/learning_sphinx_documentation)
    - [https://jameshtwose.github.io/learning_sphinx_documentation/](https://jameshtwose.github.io/learning_sphinx_documentation/)

- Learning R Shiny with Docker and Github Actions Deploy (R, Docker)
    - [https://github.com/jameshtwose/r-shiny-github-actions-deploy](https://github.com/jameshtwose/r-shiny-github-actions-deploy)
    - [https://itsamejms.shinyapps.io/mtcars-example/](https://itsamejms.shinyapps.io/mtcars-example/)

- Early Warning Signals Journal Article Supplemental Material (HTML, CSS) 
    - [https://github.com/jameshtwose/EWS-supplemental-material](https://github.com/jameshtwose/EWS-supplemental-material)

- __2021__

- Workout Chooser App (Javascript)
    - [https://github.com/jameshtwose/workout_app](https://github.com/jameshtwose/workout_app)
    - [https://workout-chooser-app.herokuapp.com](https://workout-chooser-app.herokuapp.com)

- Simple word picker (Javascript)
    - [https://github.com/jameshtwose/word_picker_js](https://github.com/jameshtwose/word_picker_js)

- Learning Continuous Integration/ Continuous Development (CICD) (Python)
    - [https://github.com/jameshtwose/learning_CICD](https://github.com/jameshtwose/learning_CICD)
    - [https://jameshtwose.github.io/learning_CICD/](https://jameshtwose.github.io/learning_CICD/)

- COVID dashboard (Python - dash, plotly)
    - [https://github.com/jameshtwose/covid-dash-jms](https://github.com/jameshtwose/covid-dash-jms)
    - [https://covid-dash-jms.herokuapp.com](https://covid-dash-jms.herokuapp.com)

- Personal fitbit dashboard (Python - dash, plotly)
    - [https://github.com/jameshtwose/fitbit-dash-jms](https://github.com/jameshtwose/fitbit-dash-jms)

- Personal fitbit analyses (Python)
    - [https://github.com/jameshtwose/jms_fitbit_analyses/tree/eda](https://github.com/jameshtwose/jms_fitbit_analyses/tree/eda)

- __2020__

- JmsTracker (Attempt 1) (Python)
    - [https://github.com/jameshtwose/jms_tracker](https://github.com/jameshtwose/jms_tracker)