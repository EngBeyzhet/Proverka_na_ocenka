# Proverka_na_ocenka
Въвеждаме оценка, проверяваме дали е отлична или не. (Проверки с if-else конструкция)

            var ocenka = double.Parse(Console.ReadLine());
            if (ocenka >= 5.50) //Ако въведената по-горе оценка е по-голямо или равно на 5.50…
            {
                Console.WriteLine("Excellent!");  //… да изпише “Excellent!”.
            }
            еlse //В противен случай…
            {
                Console.WriteLine("Bad!");  //Да изпише “Bad!”.
            }
