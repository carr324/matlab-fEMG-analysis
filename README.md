# MATLAB-fEMG-analysis
GUI-based MATLAB script to standardize EMG outputs from Mindware:

This is a user-friendly MATLAB script designed to standardize and analyze filtered electromyography (EMG) signals, specifically those outputted by [Mindware EMG software](https://www.mindwaretech.com/product_detail.asp?ItemID=557).  Parameters for the analysis are set through a GUI when the script is started, so the user doesn't need to know MATLAB to use it.  Various settings can be changed through the GUI when the script is run (e.g., baseline/trial length, standardization methods, outlier cleaning, etc.).  The script is also 100% compatible with [Octave](https://www.gnu.org/software/octave/).  Note that the code was created using Windows (so there may be a few lingering issues when porting to Mac's).

While the code should work for many types of EMG signals, it's been mostly applied to [facial EMG](https://en.wikipedia.org/wiki/Facial_electromyography) analyses thus far.  As examples, see [Carr, Winkielman, & Oveis (2014)](https://evanwalkercarr.weebly.com/uploads/3/2/3/1/32319711/carrwinkielmanoveis2013_jepg_msfinalpub.pdf) and/or [Carr, Rotteveel, & Winkielman (2016)](https://evanwalkercarr.weebly.com/uploads/3/2/3/1/32319711/carr_rotteveel___winkielman__2016__-_emotion.pdf).

For example Mindware files (or more info on the code), email Evan Carr at carr324@gmail.com.
