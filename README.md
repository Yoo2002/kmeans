# Phân loại Âm nhạc Truyền thống Việt Nam

Dự án cá nhân này tập trung vào việc phân loại các thể loại âm nhạc truyền thống Việt Nam dựa trên các đặc trưng âm sắc như Spectral Centroid, Rolloff, Flux, Zero Crossing, Low Energy và MFCC. Dự án được hoàn thành vào ngày 10/06/2024.

## Mục lục
- [Giới thiệu](#giới-thiệu)
- [Cài đặt](#cài-đặt)
- [Sử dụng](#sử-dụng)
- [Các phiên bản thư viện sử dụng](#các-phiên-bản-thư-viện-sử-dụng)
- [Quá trình thực hiện](#quá-trình-thực-hiện)
- [Tham khảo](#tham-khảo)

## Giới thiệu
Dự án này nhằm xây dựng một mô hình máy học để phân loại các thể loại âm nhạc truyền thống Việt Nam bao gồm: Cailuong, Catru, Chauvan, Cheo, và Xam. Chúng tôi sử dụng các thư viện Python để xử lý âm thanh và học máy như librosa để trích xuất đặc trưng và TensorFlow/Keras để xây dựng và huấn luyện mô hình.

## Cài đặt
Để thiết lập dự án này, bạn cần cài đặt Python 3.6+ và các thư viện cần thiết sau:

1. Clone repository:
   ```bash
   git clone https://github.com/yourusername/music-genre-classification.git
   cd music-genre-classification
