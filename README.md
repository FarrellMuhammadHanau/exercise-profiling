# Module 5
## Sebelum Optimasi
- all student
![Screenshot 2024-03-13 194231.png](Photo%2FScreenshot%202024-03-13%20194231.png)
![Screenshot 2024-03-13 195520.png](Photo%2FScreenshot%202024-03-13%20195520.png)
- all student name
![Screenshot 2024-03-13 194704.png](Photo%2FScreenshot%202024-03-13%20194704.png)
![Screenshot 2024-03-13 195605.png](Photo%2FScreenshot%202024-03-13%20195605.png)
- highest gpa
![Screenshot 2024-03-13 195153.png](Photo%2FScreenshot%202024-03-13%20195153.png)
![Screenshot 2024-03-13 195646.png](Photo%2FScreenshot%202024-03-13%20195646.png)
# Setelah Optimasi
- all student
![Screenshot 2024-03-13 204129.png](Photo%2FScreenshot%202024-03-13%20204129.png)
![Screenshot 2024-03-13 204709.png](Photo%2FScreenshot%202024-03-13%20204709.png)
- all student name
![Screenshot 2024-03-13 204158.png](Photo%2FScreenshot%202024-03-13%20204158.png)
![Screenshot 2024-03-13 204746.png](Photo%2FScreenshot%202024-03-13%20204746.png)

## Reflection
1) What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?
  Dengan menggunakan JMeter, kita dapat mengecek performa dari aplikasi dengan mengirimkan request, tetapi kita tidak mengetahui hal-hal internal seperti penggunaan method atau fungsi yang ada di aplikasi tersebut. Sementara itu, dengan IntelliJ Profiler, kita dapat mengetahui hal-hal internal seperti seberapa cepat penggunaan method, dll.
2. How does the profiling process help you in identifying and understanding the weak points in your application?
  Profiling dapat membantu mengidentifikasi dan memahami weak points karena dengan profiling saya tahu seberapa cepat atau lambat komponen pada aplikasi saya sehingga saya tahu apa yang harus saya tingkatkan atau perbaiki
3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?
  Ya, dengan Intelijj Profiler, kita dapat merecord aplikasi yang sedang jalan lalu setelah itu akan ditampilkan performa method-method yang ada pada aplikasi kita selama aplikasi kita dijalankan
4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?
   Menurut saya hambatan terbesar saat melakukan performance testing dan profiling adalah mencari tahu komponen mana yang menjadi sumber utama bottleneck pada prograam
5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?
  Dengan Intellij profiler, saya dapat dengan mudah melakukan analisis terhadap performa aplikasi saya seperti seberapa cepat method untuk selesai dijalankan, frekuensi pemanggilan method, dll.
6. How do you handle situations where the results from profiling with Inte	lliJ Profiler are not entirely consistent with findings from performance testing using JMeter?
  Saya belum menemukan ketidakkonsistenan antara intelijj profiler dan Jmeter
7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?
  Setelah melakukan performance testing dan profiling, saya akan mengidentifikasi method mana yang paling lambat. Lalu saya hanya mengoptimasi isi dari method tersebut lalu memastikan bahwa method yang sudah diubah tersebut tetap memenuhi unit test.
