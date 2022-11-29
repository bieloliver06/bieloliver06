# Hello there 👋
```c#
namespace AboutMe
{
    class Program
    {
        struct Person
        {
            public string name;
            public string location;
            public string[] spoken_languages;
            public string[] programming_languages;
        }
        static void Main(string[] args)
        {
            Person myself = new Person();
            myself.name = "Biel Oliver";
            myself.location = "Mallorca";
            myself.spoken_languages = new string[] { "english", "spanish", "catalan" };
            myself.programming_languages = new string[] { "c#", "python", "javascript" };
            Console.WriteLine("Thanks for dropping by, hope you find some of my work interesting.");
        }
    }
}
```

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=bieloliver06&hide=contribs,prs&count_private=true&show_icons=true&theme=dark)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=bieloliver06&layout=compact&theme=dark)](https://github.com/anuraghazra/github-readme-stats)
