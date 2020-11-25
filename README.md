# PerceptualEyebox

This repository contains the raw perceptual and optical data, as well as analysis scripts, from:

A perceptual eyebox for near-eye displays

Steven A. Cholewiak, Zeynep Başgöze, Ozan Cakmakci, David M. Hoffman, and Emily A. Cooper

Optics Express, in press

## 1) Perceptual data: the file “perceptual_data.csv” contains these fields for each recorded trial:

subject:	subject number

AR:		type of simulated AR (binoar: binocular AR / monoar: monocular AR)

luning:		how many eyes have vignetting (monolune: only one eye has vignetting / binolune: both eyes have vignetting)

where:		which part of the visual field is vignetted (nasal/temporal)

eyedom:		the dominance of the eye with a vignetted view (dominant/nondominant or both, determined wrt to sensory eye dominance) 

uniformity:	how uniform the image is (percentage of edge luminance relative to center: %10 least uniform, %75 most uniform)

repeat:		condition repetition number (6 repeats for each condition)

rawresp:	subject responses in their raw format (in a scale of -2 -1 0 1 2 )

pref:		subject preference (uniform or vignetted)

convresp:	recoded responses (negative responses are vignetted preferred, positive responses are uniform preferred, 2 indicates strong, 1 indicates slight)

sendomeye:	sensory dominant eye (left/right, defined by Binocular Rivalry (BR) Task)

eye:		which eye has a vignetted view, NOT-converted to dominant eye (left/right/both)

## 2) Optical data: the files "eyepiece_nonuniformities_without_eyeroll.csv" and "eyepiece_nonuniformities_with_eyeroll.csv" contain these fields for the optical element described in the manuscript:

x:		x coordinate of the pupil in mm, relative to the nominal center

y:		y coordinate of the pupil in mm, relative to the nominal center	

z:		z coordinate of the pupil in mm, relative to the eyepiece

nonuniformity:  5 point field non-uniformity	

source_center:	number of rays seen from center source at the sensor

source_left:	number of rays seen from left source at the sensor		

source_right:	number of rays seen from right source at the sensor	

source_bottom:	number of rays seen from bottom source at the sensor		

source_top:	number of rays seen from top source at the sensor	

## 3) Code: each iPython Notebook contains code for generating the indicated figures/analyses reported in the manuscript.
