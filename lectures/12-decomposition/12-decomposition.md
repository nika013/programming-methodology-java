# დეკომპოზიცია

დეკომპოზიცია არის ერთ-ერთი ყველაზე მნიშვნელოვანი და ღირებული რამ, რასაც ვსწავლობთ ამ კურსის განმავლობაში. დეკომპოზიცია არის ფიქრის პროცესი იმის შესახებ, თუ როგორ გადავჭრათ პრობლემა, რომელიც ჩვენს წინაშეა. სხვა სიტყვებით, ეს არის ფიქრის პროცესი, თუ როგორი გადაწყვეტილებები უნდა მივიღოთ ამოცანის ამოხსნისას.
როგორც წესი არის ორი ტიპის ფიქრის პროცესი და კოდის წერაში ეს უფრო კარგად ჩანს. ესენია: `top-down design` და
`bottom-up design`. დიდი ალბათობით, უმეტესობა ვინც კოდის წერას იწყებს, თავიდან ფიქრობს `bottom-up design`-ით. რას ნიშნავს გულისხმობს `bottom-up design`, როდესაც ამოცანის ამოხსნა გვინდა ვცდილობთ პატარ-პატარა ნაბიჯები გადავდგათ. თუნდაც კარელის ამოცანა იყოს, ჯერ ვფიქრობთ სად გავაკეთოთ `move()`, შემდეგ `pickBeeper()` და ასე ვცდილობთ რამენაირად ყოველგვარი სტრატეგიისა და დაგეგმარების გარეშე გავიდეთ ბოლოში. ამ ფიქრის პროცესით ბევრ პრობლემას წავაწყდებით და ნაკლებად ეფექტურია, თუმცა თავდაპირველად ყველა ასე ფიქრობს.
რაც შეეხება მეორე ფიქრის პროცესს `top-down design`-ს, როდესაც რაიმე ამოცანა გვაქვს გადასაჭრელი, ვცდილობთ ეს ამოცანა დავჭრათ უფრო მარტივ პატარ-პატარა ქვეამოცანებად, თუ ეს ქვეამოცანები ამოვხსენი ე.ი. მთლიანი ამოცანაც ამოხსნილია. მსგავსი მიდგომა, ცხადია, მიესადაგება თვითონ ამ ქვეამოცანებსაც, ანუ ისინიც რომ დავხლიჩოთ. საბოლოოდ, დავდივართ ისეთ ამოცანებამდე, რომლებიც ტრივიალურია ან უკვე გადაჭრილი აქვს ვინმეს. ეს `top-down design` ძალიან ეფექტური და კარგი ფიქრის პროცესია, რომელიც შეგვიძლია გამოვიყენოთ არა მარტო კომპიუტერულ მეცნიერებაში, არამედ ნებისმიერ სხვა დისციპლინაში და თუნდაც ცხოვრებაში. მაგალითად გვინდა შევიძინოთ მაუსი ან რაიმე ტექნიკა, ეს პრობლემა შეგვიძლია დავჭრათ ქვენაწილებად: 1. მოვიძიო მეტი ინფორმაცია მაუსების შესახებ, 2. ამოვარჩიო მათგან ისეთები, რომლებიც მაწყობს, 3. ვნახოთ ფასები და ხელმისაწვდომობა, 4. ოპტიმალური ავირჩიოთ ჩვენი კრიტერიუმების მიხედვით და 5. უშუალოდ შევიძინოთ. ცხადია, ამ ქვეამოცანების დანაწევრებაც შეიძლება, რათა თითოეული მოვაგვაროთ.
ზუსტად მსგავსი მიდგომაა კომპიუტერულ მეცნიერებაშიც. მაგალითად, თუ კარელს თუ გვინდა რაღაცები გავაკეთებინოთ, იმ დეტალებამდე უნდა მივიდეთ, რაც კარელმა უკვე იცის: `move(), pickBeeper(), turnLeft(), putBeeper()`. სანამ ამ დეტალებამდე არ ჩავალთ და არ დავაქუცმაცებთ დასმულ ამოცანას ამ დონემდე, მანამ არ გამოვა არაფერი.
დასაწყისისას საკმაოდ რთულია ამ ფიქრის პროცესს მივყვეთ, მაგრამ ძალიან მნიშვნელოვანია და უნდა შეეცადო პირველივე დავალებიდან ამ ფიქრის პროცესით ამოხსნა. ანუ უნდა შეეცადო დაჭრა ქვეამოცანებად და არ დაიწყო თუნდაც რაღაც ბრძანებების გამოძახებით ეგრევე `putBeeper()` და ა.შ.. ტვინი ისეა მოწყობილი, რომ ცდილობს პატარ-პატარა დეტალებით რამენაირად გავიდეს ბოლოში. ძალისხმევაა საჭირო და რთულია თავიდან, რომ შევეჩვიოთ `top-down design`-ით ფიქრს, თუმცა ძალიან მნიშვნელოვანია, რადგან ბევრად გაგვიმარტივებს ამოცანისა და პრობლემის ამოხსნას.