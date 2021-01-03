**ARCHIVED. See https://github.com/BillyDM/Audio-DSP-Resources instead.**

----

# dsp-learning

A bunch of resources I've come across (randomly, searching, or recommended) that I think might be useful for learning DSP concepts.

Eventually I want to organize this repo in a few different ways: beginner-to-advanced, and by-topic. I'll do that as I get more resources though.

Please let me know if there are any broken links!

## TODO

 - Add links from https://rust-audio.discourse.group/t/useful-links-for-dsp-and-audio-programming/91/4

## DSP

#### Textbooks

 - [The Scientist and Engineer's Guide to Digital Signal Processing](http://www.dspguide.com/pdfbook.htm) by Steven W. Smith
    - A decent (free!) beginner's guide to DSP. Some people like it, some people don't. YMMV.
 - [A Digital Signal Processing Primer](https://www.amazon.com/Digital-Signal-Processing-Primer-Applications/dp/0805316841) by Ken Steiglitz
    - A good beginner textbook. More or less a "getting started" guide for audio DSP.
 - [Discrete Time Signal Processing](https://www.amazon.com/Discrete-Time-Signal-Processing-3rd-Prentice-Hall/dp/0131988425) by Alan Oppenheim and Ronald Schafer
    - "The DSP Bible"
 - [Designing Audio Effect Plugins in C++](https://www.amazon.com/Designing-Audio-Effect-Plugins-C/dp/1138591939/ref=pd_lpo_sbs_14_t_1?_encoding=UTF8&psc=1&refRID=J06PKGQJVXXVV94X7DHR) by Will Pirkle
    - Also contains some good DSP theory; only math background needed is high school trig/algebra.
 - [Designing Software Synthesizer Plugins in C++](https://www.amazon.com/Designing-Software-Synthesizer-Plug-Ins-RackAFX/dp/1138787078/ref=pd_sbs_14_2/140-1426476-1774227?_encoding=UTF8&pd_rd_i=1138787078&pd_rd_r=07877825-8af5-11e9-8325-21d31ac0f1a2&pd_rd_w=mjd1w&pd_rd_wg=BFd8l&pf_rd_p=588939de-d3f8-42f1-a3d8-d556eae5797d&pf_rd_r=Q3S1N5PA30FZ44XN5RNX&psc=1&refRID=Q3S1N5PA30FZ44XN5RNX) by Will Pirkle
    - It's recommended to read the Audio Effect Plugins book first.
    - Strong DSP theory-related chapter on virtual analog filters.
 - [Applied Digital Signal Processing](https://www.amazon.com/Applied-Digital-Signal-Processing-Practice/dp/0521110025) by Dimitris Manolakis and Vinay Ingle
    - Code examples in MATLAB (almost everything is covered by GNU Octave's "signal" package)
    - Good overview of FFT, sample rate conversion, and FIR filter design theory
    - Math-heavy, but good practice problems
 - [Digital Audio Signal Processing](https://www.amazon.com/Digital-Audio-Signal-Processing-Z%C3%B6lzer/dp/0470997850) by Udo Zölzer
    - No code examples, but strong DSP theory
    - Greate chapter on IIR filter designs and discussion of topologies
 - [DAFX: Digital Audio Effects](https://www.amazon.com/DAFX-Digital-Effects-Udo-Z%C3%B6lzer/dp/0470665998/ref=pd_lpo_sbs_14_t_1?_encoding=UTF8&psc=1&refRID=XBMCPVRJ9SRA1PBA5W65) by multiple authors, edited by Udo Zölzer
    - "The digital audio cookbook"; just about all you need for music signal processing.
 - [The Art of VA Filter Design](https://www.native-instruments.com/fileadmin/ni_media/downloads/pdf/VAFilterDesign_1.1.1.pdf) by Vadim Zavalishin
    - Sort of the "jumping off point" for Zero Delay Feedback (ZDF) filters.
 - **Effect Design** by Jon Dattorro
     - [Part 1: Reverberator and Other Filters](https://ccrma.stanford.edu/~dattorro/EffectDesignPart1.pdf)
     - [Part 2: Delay-Line Modulation and Chorus](https://ccrma.stanford.edu/~dattorro/EffectDesignPart2.pdf)
     - [Part 3: Oscillators: Sinusoidal and Pseudonoise](https://ccrma.stanford.edu/~dattorro/EffectDesignPart3.pdf)
 - **Julius O. Smith** -- Lots and lots of free publications from a guy who knows his stuff.
     - [JOS Homepage](https://ccrma.stanford.edu/~jos/)
     - [Links to his books on dsprelated.com](https://www.dsprelated.com/freebooks.php)

#### Articles

 - [IIR History](http://www.rci.rutgers.edu/~shunsun/resource/IIR_History.pdf) by Charles Rader
     - Talks about the changes in "best practice" between FIR/IIR filters, it has a lot to do with available optimizations.
     - "The auther (Rader) is a DSP legend."

## Extra resources

 - [musicdsp.org](http://www.musicdsp.org/en/latest/)
    - archives of a classic mailing list covering music DSP
    - [audio-eq cookbook](https://www.musicdsp.org/en/latest/Filters/197-rbj-audio-eq-cookbook.html?highlight=audio%20eq%20cookbook) -- download this and keep it around for any filtering task you need.
 - Journal research tip: If you can't afford access, be sure to search for the paper title in google first, many authors will host the PDFs of their publications on their own pages.
 - [Google Scholar](https://www.kvraudio.com/forum/viewforum.php?f=33&sid=c5ec6fcced363b6102b21b5be3b843c0)
    - Useful for seeing number of citations. "In audio, 5+ citations usually means you did something right."
 - [sci-hub](https://en.wikipedia.org/wiki/Sci-Hub)
    - Not going to link to this directly...
 - [IEEE transactions on Audio, Speech, and Language processing](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10376)
    - One of the preeminent journals for audio DSP, but rarely focused on music.
 - [Digital Audio FX (DAFX)](http://www.dafx.de/)
    - Yearly (open) publication covering audio effects and music signal processing.
 - [Journal of the Audio Engineering Socieity (j.AES)](http://www.aes.org/e-lib/)
    - Excellent e-library, membership is totally worth it.
    - Good home base for researching the state-of-the-art for whatever problem you're trying to solve.
    - Has a number of seminal publications, like Linkwitz-Riley filters, FM synthesis, etc.
 - [CCRMA](https://ccrma.stanford.edu/)
    - One of the most respected music/audio research institutions in America.
    - Has a large number of HTML resources for music.
 - **Forums**
    - [Rust Audio Discourse Group](https://rust-audio.discourse.group/) (shameless plug)
    - [/r/dsp](https://www.reddit.com/dsp)
    - [KVR DSP & Plugin Development](https://www.kvraudio.com/forum/viewforum.php?f=33&sid=c5ec6fcced363b6102b21b5be3b843c0)
    - [JUCE forum](https://www.forum.juce.com)
