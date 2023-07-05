# Summary

## 1. Name and Surname
Yaroslav Zastolskiy

## 2. Contacts
- Phone: +375(29)3655279
- Email: boss251710@gmail.com
- GitHub: https://github.com/Fi0uF
- VK: https://vk.com/fi0uf

## 3. Brief information about yourself
I am a second-year student of the Belarusian-Russian University. My goal is constant growth and development. I believe that learning and gaining new knowledge are the achievements of success.
I want to constantly learn and gain new knowledge and experience. With a passion for satisfaction as well as a propensity to meet new challenges, I am confident in my ability to make a meaningful contribution to any project.

## 4. Skills
Hard skills:
- Programming languages: C#.
- Development tools: Visual Studio, Visual Studio Code.
   
Soft skills:
- Problem solving: the ability to analyze complex problems and find the best solutions.
- Adaptability: be flexible and open to learning new programming languages, frameworks and tools as technology evolves.
- Teamwork: cooperation with other people, participation in group projects.
- Analytical thinking: applying logical thinking skills to analyze problems and make the right decisions.
- Continuous learning: willingness to keep abreast of the latest trends, tools and methods in software development.
  

## 5. Code examples
```C#
using System;
using System.IO;
namespace ConsoleApp
{
     const int n = 5, m = 5;
 
            int[,] Mas1 = new int[m, n];
            int[,] Mas2 = new int[m, n];
            Random rand = new Random();
 
            for (int j = 0; j < n; j++)
            {
                for (int i = 0; i < n; i++)
                {
                    Mas1[i, j] = rand.Next(0, 10);
                    Console.Write(Mas1[i, j]);
                }
                Console.WriteLine();
            }
            Console.WriteLine();
            for (int j = 0; j < n; j++)
            {
                for (int i = 0; i < n; i++)
                {
                    Mas2[i, j] = Mas1[(n - 1) - i, j];
                    Console.Write(Mas2[i, j]);
                }
                Console.WriteLine();
            }
            Console.ReadKey();
}
```
## 6. Work experience and training projects
I graduated from the second year of the Belarusian-Russian University.

## 7. Languages
- Russian - Native
- English - A1 Beginner

## 8. Photo
![photo](/image.jpg)
