# Hello Everyone!
My name is Rahmat Pratami
I'am software engineer student from Telkom University

Let's Connected! [Linkedin](https://www.linkedin.com/in/rahmat-pratami-027709247/)

<p align="left">
<a href="https://github.com/R1zarD9K">
  <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=R1zarD9K&show_icons=true&theme=algolia&include_all_commits=true&count_private=true"/> <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=R1zarD9K&layout=compact&langs_count=8&theme=algolia"/> <img height="240em" src="https://github-readme-stats.vercel.app/api/wakatime?username=R1zarD9K&show_icons=true&theme=algolia&include_all_commits=true&count_private=true"/>
</a>
</p>
# Submission 1: Machine Learning Pipeline - Food Review Prediction
Nama: Rahmat Pratami

Username dicoding: r1zard9k

![Food Review](https://feedbacklabs.org/wp-content/uploads/2020/08/iStock-911978098-1254x627.jpg)


| | Deskripsi |
| ----------- | ----------- |
| Dataset | [Food Review Prediction](https://www.kaggle.com/datasets/d4rklucif3r/restaurant-reviews) |
| Masalah | Restoran sering kali menawarkan berbagai macam menu. Dengan menganalisis ulasan makanan dari pelanggan, restoran dapat memahami preferensi pelanggan dan menyesuaikan menu mereka untuk meningkatkan kepuasan pelanggan. Food Review Prediction dapat membantu dalam memahami tren dan preferensi pelanggan berdasarkan ulasan yang diterima. |
| Solusi machine learning | Dengan menganalisis ulasan makanan, model machine learning dapat memberikan rekomendasi untuk menu yang dapat ditingkatkan atau diubah. Misalnya, jika sebagian besar ulasan negatif terkait dengan suatu item menu tertentu, restoran dapat mempertimbangkan untuk menghapus atau memodifikasi item tersebut. |
| Metode pengolahan | Data ulasan awal pelanggan akan dibagi menjadi data pelatihan dan evaluasi dengan rasio 80:20. Selanjutnya, data akan divalidasi untuk mengidentifikasi anomali dan kemudian diproses untuk siap untuk pelatihan. Setelah pelatihan selesai, model akan dievaluasi dan dikirim ke endpoint yang siap untuk digunakan. |
| Arsitektur model | Arsitektur yang digunakan cukup sederhana, terdiri dari layer Embedding dan satu layer Dense sebagai lapisan yang tersembunyi. Karena ini adalah klasifikasi binar, fungsi aktivasi pada lapisan output menggunakan Sigmoid.|
| Metrik evaluasi | Metrik evaluasi yang digunakan yaitu ExampleCount, AUC, FalsePositives, TruePositives, FalseNegatives, TrueNegatives, dan BinaryAccuracy |
| Performa model | Model memiliki performa antara lain adalah loss: 0.0375 - binary_accuracy: 0.9867 - val_loss: 2.9394 - val_binary_accuracy: 0.6766. Untuk False Negatives 34, False Positive 31, True Negative 64 dan True Positive 72. Model yang telah dibuat dapat dilakukan peningkatan performa, karena model belum cukup baik karena BinaryAccuracy masih dibawah 80% |
