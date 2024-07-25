# acd_class_mapping
## Audioset mapping to super-classes as used in: Multi-label audio classification with a noisy zero-shot teacher

The .csv file contains Audioset classes collated into super-classes for audio content detection. We used these 11 classes:
| class | description |
|-------|-------------|
| voice | includes all human-uttered voice sounds like speech, singing in all variants. Excludes caughing, snoring, throat clear, sniff |
| music | all music. A capella/voice choir is also music! |
| cat | cat sounds |
| dog | dog sounds |
| clapping | hand clapping and applause | 
| urban | all sounds that can occur in urban environments, e.g. cars, traffic, pedestrians, sirens, etc. |
| machinery | all machine and industrial sounds |
| nature | all non-human sounds occuring in nature, e.g. animals, wind, water, fire, etc. |
| windnoise | distorting microphone due to wind |
| alarm | all alarms and sirens |
| gunshot | includes gunshots and explosions |

The first column contains unused classes, that have not been assigned to any super-class, just for reference.

## Corresponding publication: 
https://arxiv.org/abs/2407.14712

Sebastian Braun, Hannes Gamper, Multi-label audio classification with a noisy zero-shot teacher, in Proc. International Workshop on Acoustic Signal Enhancement (IWAENC) 2024.
