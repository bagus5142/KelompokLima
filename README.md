# KelompokLima
PROJEK Desain &amp; Analisis Algoritma yang bertema Sudoku - Solver

Repository ini berisi program eksperimen untuk membandingkan performa algoritma penyelesaian Sudoku(sudoku solver), yaitu dengan menggunakan:

- MRV (Minimum Remaining Value) + Backtracking
- Forward Checking (FC) + Backtracking

===============================Before Running==============================
Program dijalankan menggunakan Jupyter Notebook (Python 3.11) dan menghasilkan:

- File  hasil eksperimen
- Grafik perbandingan (PNG)
- Tabel ringkasan (LaTeX)
- Dashboard HTML interaktif (case-by-case)
--------------------------------------------------------------------------

===============================Library==============================
Untuk menjalankan notebook, pastikan sudah menginstall library library dibawah ini

- os, time, random, statistics
- sys
- Path
- List, Tuple, Optional, Any, Dict, Set
- numpy
- pandas
- matplotlib.pyplot 
--------------------------------------------------------------------

===============================Parameter yang akan digunakan==============================
Sebelum masuk ke kode utama, tentukan parameter eksperimen terlebih dahulu, bisa dilihat di CELL 1 bagian berikut ini :

TIMEOUT_SEC = 90 ---> batas waktu per Sudoku (dalam detik)
REPEATS = 1 ---> jumlah pengulangan (disarankan 1 untuk speed test, dan mengurangi waktu running)
------------------------------------------------------------------------------------------

===============================Running notebook==============================
Jalankan notebook secara berurutan dari CELL 1 sampai CELL 9.

Ringkasan Fungsi Setiap Cell

Cell	Fungsi
1. 	    Import library & konfigurasi
2.	    Implementasi class SudokuSolver
3.	    Definisi algoritma MRV & FC
4.	    Loader dataset
5.	    Evaluator & pengukuran waktu
6.	    Eksekusi eksperimen utama
7.	    Visualisasi grafik
8.	    Ekspor tabel LaTeX
9.	    Pembuatan dashboard HTML
----------------------------------------------------------------------------

===============================Output==============================
Setelah seluruh cell dijalankan, folder result/ akan berisi:

- summary.tex : tabel siap LaTeX
- PNG grafik : waktu, node, success rate
- dashboard_sudoku_case_by_case.html : visualisasi solusi per puzzle
-------------------------------------------------------------------
