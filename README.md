# Welcome

This model was prepared as an assignment for classes *Multi-agent modeling*. It uses `Julia` language, Version 1.1.0 

**NOTE** This is just a simple simulation project, I'm not convinced that it imitates reality well enough, as I don't have specialist knowledge in this subject.

This model simulates the process of epidemic disease spread. In particular, it raises the problem of **herd immunity**, which is a form of defence against epidemic diseases, which protects people that can't (or won't) be vaccinated, because when the majority of population is vaccinated (immune), then the disease can't spread.

The greater the proportion of immune ones (either in natural way or vaccinated), the lower the chance that those endangered will have contact with the disease. In case of, for example measles or smallpox, the *herd immunity threshold* is estimated to be 92-95% for the first one and 80-86% for the latter.  
The contact with infected person is necessary for these diseases to spread.

The model performs a simulation of a hypothetical disease, that can be spread by contact with infected ones.
  
  
__Sources__  
* [Fine P., Eames K., Heymann D. L.. "Herd immunity": A rough guide. „Clinical Infectious Diseases”](https://academic.oup.com/cid/article/52/7/911/299077).
* [Vanderslott S., Roser M., "Vaccination"](https://ourworldindata.org/vaccination#how-vaccines-work-herd-immunity-and-reasons-for-caring-about-broad-vaccination-coverage).
