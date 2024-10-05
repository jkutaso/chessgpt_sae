# Interpretability of SAE features trained on ChessGPT

This is the repo for our (Jon Kutasov and David Steinberg) ARENA capstone project. The writeup of  our results is here: https://www.lesswrong.com/posts/k77qQ5J7LPr9WEuDk/interpretability-of-sae-features-representing-check-in

The analysis is split over several notebooks:
- when_do_features_fire.ipynb will gather the data and generate plots showing our analysis of where in the PGN pattern features fire
- logit_attribution.ipynb shows the effect of intervening at the SAE stage in various ways
- latent_activation_prediction.ipynb does the logic for testing if the custom function method described can do a good job describing SAE features
- SAE_check_without_plus.ipynb does the analysis of what happens when we omit the + in the PGN string

The other notebooks and files are either copied from the original paper or do some preliminary exploration. They don't contain interesting results but may be valuable for someone who is trying to build on the same repo as us.
