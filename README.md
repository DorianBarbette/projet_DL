#  Reconnaissance des émotions dans la parole

Il s'agit d'un autre projet de Deep learning (DL) dans lequel vous devez traiter principalement des
données audio. La reconnaissance des émotions vocales tente d'identifier et d'interpréter les
émotions de l'utilisateur et de déduire l'état émotionnel à partir du discours. Pour entraîner un tel
algorithme, vous devez utiliser la plupart des données d'entraînement sous forme de données audio.
Ce système prend le discours de l'utilisateur en entrée. Outre les bibliothèques Python générales
telles que NumPy, Pyaudio et Soundfile, vous pouvez également utiliser Librosa. Librosa est une
bibliothèque Python qui permet d'analyser les données audio et les fichiers musicaux. 
Ce projet nécessite l'ensemble de données RAVDESS1 pour entraîner le modèle d'apprentissage
automatique avec différents types d'audio. L'ensemble de données RAVDESS (Ryerson AudioVisual Database of Emotional Speech and Song) contient 7356 fichiers avec des échantillons de voix de 24 acteurs professionnels 
(12 femmes, 12 hommes). Il comprend différentes intensités de discours,
comme des expressions joyeuses, calmes, en colère, tristes, surprenantes, 
craintives et de dégoût, ainsi que des chansons aux émotions diverses, comme tristes, 
joyeuses, effrayantes, paisibles et féroces

Filename identifiers :

Modality (01 = full-AV, 02 = video-only, 03 = audio-only).
Vocal channel (01 = speech, 02 = song).
Emotion (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised).
Emotional intensity (01 = normal, 02 = strong). NOTE: There is no strong intensity for the ‘neutral’ emotion.
Statement (01 = “Kids are talking by the door”, 02 = “Dogs are sitting by the door”).
Repetition (01 = 1st repetition, 02 = 2nd repetition).
Actor (01 to 24. Odd numbered actors are male, even numbered actors are female).
Filename example: 02-01-06-01-02-01-12.mp4

Video-only (02)
Speech (01)
Fearful (06)
Normal intensity (01)
Statement “dogs” (02)
1st Repetition (01)
12th Actor (12)
Female, as the actor ID number is even.
APPENDIX 2: The TESS dataset