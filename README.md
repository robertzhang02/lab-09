[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-8d59dc4de5201274e310e4c54b9627a8934c3b88527886e3b421487c677d23eb.svg)](https://classroom.github.com/a/aT9CtJYb)
# Lab 8
[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repo and clone it to your machine to get started!

## Team Members
- team member 1: Jiansong Li
- team member 2: Robert Zhang

## Lab Question Answers

Question 1: What is the phone number dialed in sample3.py?

Answer: 5055034455

Question 2: Describe your algorithm. Explain what each of these functions do: get_peak_frqs(), get_max_frq(), and get_number_from_frq().

Answer: The function of get_peak_frqs() basically return the two highest frequencies from the splitted FFT arrays. The first one correspond to the frequency with highest amplitude in the first array which spans from 0 to 1000hz. And the seoncd one correspond to the frequency with highest amplitude in the second which spans from 1000 to 2000hz. 
        The function of get_max_frq() is used to find the corresponding frequency which has the highest amplitude in the given FFT array. Through the combination of get_peak_frqs() and get_max_frq(), we are able to get the two highest frequcies that could be useful for the decoding part later on.
        The function of get_number_from_frq() will generate the number that corresponds to the given two highest frequencies by checking with the NUMBER_DIC dictionary. The two useful index are from the previous function of get_peak_frqs() and get_max_frq(), which are named lower_frq and higher_frq. 

	
