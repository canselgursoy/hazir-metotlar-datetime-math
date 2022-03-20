Console.WriteLine("***********************");
Console.WriteLine(DateTime.Now);
Console.WriteLine(DateTime.Now.Date);
Console.WriteLine(DateTime.Now.Day);
Console.WriteLine(DateTime.Now.Month);
Console.WriteLine(DateTime.Now.Year);
Console.WriteLine(DateTime.Now.Hour);
Console.WriteLine(DateTime.Now.Minute);
Console.WriteLine(DateTime.Now.Second);

Console.WriteLine("***********************");
Console.WriteLine(DateTime.Now.DayOfWeek);
Console.WriteLine(DateTime.Now.DayOfYear);

Console.WriteLine("***********************");
Console.WriteLine(DateTime.Now.ToLongDateString());
Console.WriteLine(DateTime.Now.ToShortDateString());
Console.WriteLine(DateTime.Now.ToLongTimeString());
Console.WriteLine(DateTime.Now.ToShortTimeString());

Console.WriteLine("***********************");
Console.WriteLine(DateTime.Now.AddDays(2));
Console.WriteLine(DateTime.Now.AddHours(2));
Console.WriteLine(DateTime.Now.AddMilliseconds(2));
Console.WriteLine(DateTime.Now.AddMinutes(2));
Console.WriteLine(DateTime.Now.AddMonths(2));
Console.WriteLine(DateTime.Now.AddSeconds(2));
Console.WriteLine(DateTime.Now.AddYears(2));


//DateTime Format
Console.WriteLine("***********************");
Console.WriteLine(DateTime.Now.ToString("dd")); //21
Console.WriteLine(DateTime.Now.ToString("ddd")); // mon
Console.WriteLine(DateTime.Now.ToString("dddd")); // monday

Console.WriteLine("***********************");
Console.WriteLine(DateTime.Now.ToString("MM")); // 03
Console.WriteLine(DateTime.Now.ToString("MMM")); // MAR
Console.WriteLine(DateTime.Now.ToString("MMMM")); // MARCH

Console.WriteLine("***********************");
Console.WriteLine(DateTime.Now.ToString("yy")); // 22
Console.WriteLine(DateTime.Now.ToString("yyyy")); // 2022


//Math Kütüphanesi
Console.WriteLine("*********math kütüphanesi**************");
Console.WriteLine(Math.Abs(-25)); //mutlak değer
Console.WriteLine(Math.Sin(10)); 
Console.WriteLine(Math.Cos(10)); 
Console.WriteLine(Math.Tan(10)); 

Console.WriteLine(Math.Ceiling(22.3)); // 23 yukarı yuvarlar
Console.WriteLine(Math.Round(22.3)); // 22 normal yuvarlama-nereye yakınsa
Console.WriteLine(Math.Round(22.7)); // 23 normal yuvarlama-nereye yakınsa
Console.WriteLine(Math.Floor(22.7)); // 22 aşağı yuvarlar

Console.WriteLine(Math.Max(2,6));
Console.WriteLine(Math.Min(2,6));

Console.WriteLine(Math.Pow(3,4)); //3üssü 4
Console.WriteLine(Math.Sqrt(9)); //karekök
Console.WriteLine(Math.Log(9)); //9 un e tabanındaki logaritmik karşılığını verir
Console.WriteLine(Math.Exp(9)); // e üssü 9 u verir
Console.WriteLine(Math.Log10(10)); // 10 sayısının logaritma 10 tabanındaki karşılığını verir





