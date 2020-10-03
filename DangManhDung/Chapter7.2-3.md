Tính bao hàm có một điểm yếu đáng kể. Cho rằng tiêu chuẩn *C<sub>strong</sub>* bao hàm tiêu chuẩn *C<sub>weak</sub>* và bộ kiểm thử *T<sub>strong</sub>* thoả mãn *C<sub>strong</sub>*, bộ kiểm thử *T<sub>weak</sub>* thoả mãn *C<sub>weak</sub>*. Không nhất thiết là *T<sub>weak</sub>* là bộ con của *T<sub>strong</sub>*. Cũng không nhất thiết là *T<sub>strong</sub>* hiện ra một lỗi khi *T<sub>weak</sub>* phát hiện ra lỗi. Giải thích giả thuyết trên.

* Lý do là sự bao hàm *C<sub>weak</sub>* của *C<sub>strong</sub>* không nói lên mối quan hệ tập hợp con giữa *T<sub>weak</sub>* và *T<sub>strong</sub>*. Có nhiều kiểm thử để đáp ứng một yêu cầu kiểm thử nhất định. Khi có một yêu cầu kiểm thử chung cho cả *C<sub>weak</sub>* và *C<sub>strong</sub>*, chắc chắn có thể chọn một bài kiểm thử cho *T<sub>weak</sub>* và một bài kiểm thử khác cho *T<sub>strong</sub>*. Vậy nên, kiểm thử tiết lộ lỗi có thể được chọn với *T<sub>weak</sub>*, nhưng không được chọn với *T<sub>strong</sub>*.