# C-sharp_ClassPractice
C# personal or team homwork display

### 作業1（HW-1.zip）
1. BMI計算機：提示使用者輸入身高體重，讀取使用者輸入的值，計算並顯示使用者的BMI，判斷使用者為過輕、適中或過重。
   BMI Calculator: This application prompts the user to input height and weight, reads the provided values, calculates the user's Body Mass Index, and determines whether the user is underweight, normal weight, or overweight.
2. 聖誕樹：提示使用者輸入樹的大小，使用者輸入的大小即為每個三角形的高度，樹由兩個三角形及長方形樹幹組成。
   Christmas Tree Generator: This program prompts the user to input the size of the tree, where the entered size represents the height of each triangle. The tree is composed of two triangles and a rectangular trunk.
3. 身分證檢核程式：提示使用者輸入身分證字號，讀取使用者輸入的值，判斷使用者的身分證字號合法或非法。
   ID Validation Program: This utility prompts the user to input their national identification number, reads the provided value, and assesses the legitimacy of the entered ID, determining whether it is valid or invalid.

### 作業2（HW-2.zip）
1. 統一發票對獎：準備中獎規則 (包含與中獎號碼比對中幾碼得多少獎金)，提示使用者輸入發票號碼，檢查輸入格式是否正確 (8 碼、皆數字)。
   由大獎至小獎，號碼由右至左比對，如果中獎，顯示「恭喜您獲得X獎XXX元」。
   如果沒中，顯示沒中獎，使用者輸入字母「Q」，結束程式。
   Uniform Invoice Prize Checking: Preparation of winning rules (including the comparison of the entered invoice number with the winning numbers, specifying the reward based on the matched digits), prompting the user to input the invoice number, and checking the input format for correctness (8 digits, all numeric). Starting from the grand prize to the smaller prizes, the numbers are checked from right to left. If there is a match, display "Congratulations! You have won the X prize, NT$XXX." If not, display "No winning." The user can input the letter "Q" to end the program.
2. 1A2B(自己猜)：利用亂數產生一組四碼的正確答案 • 四碼皆為小於等於 9 的整數（四碼不可重複）。
   提示使用者輸入答案，電腦檢查答案，並顯示XAYB（X 表示位置正確的數的個數，Y 表示數字正確而位置不對的數的個數）。
   使用者輸入正解或字母「Q」，結束遊戲。
   使用者輸入「AAAA」，電腦需顯示正解，檢核使用者輸入資料是否為4碼、皆為整數且不重複。
   1A2B (Guessing Game): Generating a correct answer of four digits using random numbers. All four digits are integers less than or equal to 9 and are unique. Prompting the user to input their guess, the computer checks the answer and displays XAYB (where X represents the number of correctly positioned digits, and Y represents the number of digits that are correct but in the wrong position). The user can input the correct answer or the letter "Q" to end the game. If the user inputs "AAAA," the computer should display the correct answer and check if the user input is a 4-digit integer with unique digits.
3. Hangman：從老師所提供之 wordLibrary 中隨機挑選一個單子來當答案，需要字數提示。
   讓使用者猜字母，依照使用者猜的字母分兩種情境：
   (1) 猜對的情境：顯示猜對的字母，若全部的字都猜對，則遊戲結束;反之則回到步驟 3 讓使用 者繼續猜字母。
   (2) 猜錯的情境：依照猜錯的次數配合專案範例的 DrawHangman 來畫出 「上吊的人」，累積 5 次錯誤時則遊戲結束。
   Hangman: Randomly selecting a word from the provided word library with a hint about its length. Allowing the user to guess letters, two scenarios arise based on the user's input:
   (1) Correct guess: Displaying the correctly guessed letters. If all letters are guessed correctly, the game ends. Otherwise, return to step 3 for the user to continue guessing.
   (2) Incorrect guess: Drawing the "hanged man" based on the number of incorrect guesses, following the example in the DrawHangman project. The game ends when there are 5 accumulated incorrect guesses.
   
### 團體作業1（TW-1.zip）
製作一可以查詢書籍資料之 windows form，可供使用者利用書名、購買日期、書本種類等做查詢。並可以進行新增、刪除與修改之功能。並且可以記錄書本之借閱狀態，並記錄借閱者。
我主要負責SQL部分、檢查程式碼與上台Demo。
Developing a Windows Form application for querying book information is proposed, enabling users to search based on book title, purchase date, book category, and other criteria. The application supports functionalities such as adding, deleting, and modifying records. Additionally, it facilitates the tracking of the borrowing status of books and maintains a record of the borrowers. My primary responsibilities include managing the SQL component, code validation, and presenting the demonstration.

### 團體作業2（TW-2.zip）
待更新
