# fbank-mfcc

understand mfcc feature extraction.

stft(短时傅里叶变换 加窗分帧+fft) -> fbank (stft 之后得到功率谱，再到mel scale) -> mfcc (fbank DCT变换进行解偶)
