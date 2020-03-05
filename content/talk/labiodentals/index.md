+++
title = "Labiodentals /r/ here to stay: Deep learning explains why"
date = 2019-02-15T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2020-03-28T14:00:00
#time_end = 2019-06-05T15:18:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Hannah King", "Emmanuel Ferragne"]

# Abstract and optional shortened version.
abstract = ""
abstract_short = ""

# Name of event and optional event URL.
event = "20th ALOES Conference on Spoken English "
event_url = "https://aloesfrance.wordpress.com/recherche/colloques-davril-de-villetaneuse-sur-langlais-oral/"

# Location of event.
location = "Villetaneuse, France"

# Is this a featured talk? (true/false)
featured = true

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects = ["internal-project"]
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Phonetics", "Deep Learning"]

# Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  #caption = "Photo by Linh Nguyen on Unsplash"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++
Articulatory variation has been well-documented in approximant realisations of English /r/.  Despite the diversity of tongue shapes [1–3], the acoustic profile of /r/ is relatively stable [4], characterised by a very low F3 [1,5,6] close to F2 [7,8]. However, the production of /r/ remains enigmatic, especially concerning non-rhotic Englishes and the accompanying labial gesture. The lips are particularly pertinent to Anglo-English /r/ because high-F3 labiodental variants are rapidly gaining currency [9,10]. Labiodentalization may be due to speakers retaining the labial gesture at the expense of the lingual one [9,11,12], implying that /r/ is always labiodental even in lingual productions. We verify this assumption by comparing the labial postures of /r/ and /w/ in Anglo-English speakers who still present a lingual component. If /r/ is labiodental, the labial gesture for /w/, which is unequivocally considered rounded, should differ considerably.

We recorded 23 (21F) native speakers from England reading /r-w/ minimal pairs using ultrasound tongue imaging and a front lip camera. Ultrasound confirmed that subjects produced a lingual gesture for /r/, presenting similar patterns of variation to the continuum of possible tongue shapes reported in rhotic varieties of English, i.e. from curled up retroflex to tip down bunched [1–3,13]. In women, F3 was around 800 Hz lower and F2 500 Hz higher for /r/ than /w/ on average. The image corresponding to maximal labial constriction was manually selected from 414 lip videos. A deep convolutional neural network used these images to automatically learn the difference between /r/ and /w/. The very high accuracy of the model (near 100% for most subjects) supported the sufficiently discriminant role of lip configuration; and occlusion analysis [14] confirmed that the model relied on the lips. In order to get a more detailed understanding in articulatory terms, another deep neural network [15] was trained to automatically segment the lips from the rest of the images. This allowed us to obtain consistent measurements of lip width and vertical position. 

Results indicate that the lips differ significantly for /r/ and /w/. The lip corners are brought together at the centre for /w/, whereas for /r/, the lips are protruded upwards, presumably resulting in the bottom lip approaching the upper teeth, thus providing a phonetic account for labiodentalization. The question remains why the labial postures for /r/ and /w/ vary. It has been suggested that rounding in front and back vowels differs in order to enhance the perceptual contrast between them [16]: front vowels are produced with less lip corner contraction to avoid over-lowering F2 [17]. The same strategy may be used to enhance the /r-w/ contrast: /r/ has significantly less horizontal contraction than /w/, ensuring F2 remains in close proximity to F3. Our future research will assess whether these different labial gestures are perceptibly salient.

**References**

1 	Delattre, P. and Freeman, D.C. (1968) A dialect study of American r’s by x-ray motion picture. Linguistics 6, 29–68

2 	Tiede, M.K. et al. (2004) A new taxonomy of American English /r/ using MRI and ultrasound. The Journal of the Acoustical Society of America 115, 2633–2634

3 	Zawadzki, P.A. and Kuehn, D.P. (1980) A Cineradiographic Study of Static and Dynamic Aspects of American English /r/. Phonetica 37, 253–266

4 	Espy-Wilson, C.Y. et al. (2000) Acoustic modeling of American English /r/. The Journal of the Acoustical Society of America 108, 343–356

5 	Boyce, S. and Espy-Wilson, C.Y. (1997) Coarticulatory stability in American English /r/. The Journal of the Acoustical Society of America 101, 3741–3753

6 	Proctor, M. et al. (2019) Articulatory characterization of English liquid-final rimes. Journal of Phonetics 77, 100921

7 	Guenther, F.H. et al. (1999) Articulatory tradeoffs reduce acoustic variability during American English /r/ production. The Journal of the Acoustical Society of America 105, 2854–2865

8 	Stevens, K.N. (1998) Acoustic phonetics, MIT Press.

9 	Docherty, G. and Foulkes, P. (2001) Variability in r production-instrumental perspectives. In ’R-atics: Sociolinguistic, phonetic and phonological characteristics of /r/ (Van de Velde, H. and van Hout, R., eds), pp. 173–184, Université Libre de Bruxelles

10 	Marsden, S. (2006) A sociophonetic study of labiodental /r/ in Leeds. Leeds Working Papers in Linguistics and Phonetics 

11 	Foulkes, P. and Docherty, G.J. (2000) Another chapter in the story of /r/: ‘Labiodental’ variants in British English. Journal of sociolinguistics 4, 30–59

12 	Jones, D. (1972) An Outline of English Phonetics, 9th Edition. Cambridge University Press.

13 	Lawson, E. et al. (2011) The social stratification of tongue shape for postvocalic /r/ in Scottish English. Journal of Sociolinguistics 15, 256–268

14 	Zeiler, M.D. and Fergus, R. (2014) Visualizing and Understanding Convolutional Networks. In Computer Vision – ECCV 2014 8689 (Fleet, D. et al., eds), pp. 818–833, Springer International Publishing

15 	Chen, L.-C. et al. (2018) Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation. In Computer Vision – ECCV 2018 11211 (Ferrari, V. et al., eds), pp. 833–851, Springer International Publishing

16 	Catford, J.C. (1977) Fundamental problems in phonetics, Edinburgh University Press.

17 	Wood, S. (1986) The acoustical significance of tongue, lip, and larynx maneuvers in rounded palatal vowels. The Journal of the Acoustical Society of America 80, 391–401
