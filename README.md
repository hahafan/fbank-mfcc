# fbank-mfcc

understand mfcc feature extraction.

stft(短时傅里叶变换 加窗分帧+fft) -> fbank (stft 之后得到功率谱，再到mel scale) -> mfcc (fbank DCT变换进行解偶)

but different tools generate different fbank/mfcc feature, cause they have different settings(such as window, bins, window-shift...). So, if we use two different tools or implement by ourselves, we need make sure all the settings are same.  
