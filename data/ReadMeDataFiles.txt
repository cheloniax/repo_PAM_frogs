### frog_data.csv

#### Variables
date.time: Date and time of the detection.
date: Date of the detection.
site: One of six survey site sampled in this study.
plot: One of four survey plots found within each site.
common.name: Species common name based on the Australian Faunal Directory (https://biodiversity.org.au/afd/home).
scientific.name: Species scientific name based on the Australian Faunal Directory (https://biodiversity.org.au/afd/home).
family: Species family name based on the Australian Faunal Directory (https://biodiversity.org.au/afd/home).
assessment.method: One of three methods compared to detect frogs in this study. OBM = observer-based monitoring, PAM.all = passive acoustic monitoring with all available audio data, PAM.survey = passive acoustic monitoring with audio data only matching the OBM survey periods.
SamplingPeriod: The season and year each frog detection ocurred.
survey.method: One of seven individual survey methods detect frogs in this study. funnel = Funnel trap, pitfall = Pitfall trap, spotlighting = Spotlight survey, incidentals = Incidental encounters, cover board = Arboreal cover board, PAM.all = passive acoustic monitoring with all available audio data, PAM.survey = passive acoustic monitoring with audio data only matching the OBM survey periods.
SamplingDay: The number represents the sampling day in order for each method. For example SamplingDay = 1 means the first day this method started sampling for frogs.

### frogs_PAM_daily_all.csv

#### Variables
MANUAL.ID: Validation of each detection by BirdNET feature embeddings. TRUE = true positive detection (i.e., detection matches the species example call vocalisation), FALSE = false positive detection (i.e., detection does not match the species example call vocalisation)
template: One of 115 example calls for 50 species of Australian frogs.
eucledian.distance: Value for the shortest euclidean distance (best match for example call and unknown audio clip) for each day of audio recording.

### frog_data_season.csv

#### Variables
ate.time: Date and time of the detection.
date: Date of the detection.
site: One of six survey site sampled in this study.
plot: One of four survey plots found within each site.
common.name: Species common name based on the Australian Faunal Directory (https://biodiversity.org.au/afd/home).
scientific.name: Species scientific name based on the Australian Faunal Directory (https://biodiversity.org.au/afd/home).
family: Species family name based on the Australian Faunal Directory (https://biodiversity.org.au/afd/home).
assessment.method: One of three methods compared to detect frogs in this study. OBM = observer-based monitoring, PAM.all = passive acoustic monitoring with all available audio data, PAM.survey = passive acoustic monitoring with audio data only matching the OBM survey periods.
season: The season each frog detection ocurred.
SamplingDay: The number represents the sampling day in order for each method. For example SamplingDay = 1 means the first day this method started sampling for frogs.
Sampling.trip: The site, season and year each frog detection ocurred.

### expenses_daily.csv

#### Variables
trip: One of four survey trips over the course of the study.
date: Date of the expense.
item: Item of the expense.
category: Category of the expense.
method: Whether the expense was related to PAM or OBM.
cost: The cost incurred in AUD.
cost_per_item: Cost broken down by individual items.
number_of_items: Number of items purchased.
notes: Any further information on the origin of the expense.