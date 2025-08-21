SQL-də normalizasiya nədir? DBA-da rolu nə dərəcədə mühümdür?

SQL-də Normalizasiya — verilənlər bazasında məlumatların təkrarlanmasının qarşısını almaq, məlumat bütövlüyünü qorumaq və məlumatların daha səmərəli idarə olunmasını təmin etmək üçün tətbiq olunan bir prosesdir.
Normalizasiyanın məqsədi:
1. Redundansın (təkrarın) azaldılması
2. Anomalilərin qarşısının alınması
 (məs: əlavəetmə, silmə və yeniləmə zamanı yaranan problemlər)
3. Məlumatların strukturlaşdırılması və əlaqələndirilməsi
4. Verilənlər bazasının daha çevik və effektiv saxlanması

3 əsas səviyəmiz var: 
1NF(birinci normal forma),
2NF(ikinci normal forma),
3NF(üçüncü normal forma)

1NF - Hər sütun atomik dəyər saxlamalıdır.
2NF - Əgər cədvəldə composite key varsa, onda digər sütunlar həmin composite key-in tam olaraq hər ikisinə bağlı olmalıdır, tək bir hissəsinə yox.
3NF - Cədvəldə heç bir primary key olmayan column digər primary key olmayan column-dan transitiv şəkildə olmamalıdır.
