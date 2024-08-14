# C# and .Net Roadmap

# Summary

This roadmap guides your journey through the exciting world of C# and .NET development, catering to both beginners and experienced programmers. It provides a structured path for learning and progression, outlining key topics and resources.

| Table of contents                                                                  |
| ---------------------------------------------------------------------------------- |
| [Database Design & SQL](#database-design--sql)                                     |
| [Programming Fundamentals & C# Syntax](#master-programming-fundamentals--c-syntax) |
| [Entity Framework Core](#entity-framework-core) |

# Part 1: Learning Your Way Up

## Foundation (Beginner)

### Database Design & SQL

> [!Note]
> you can choose any DBMS but **MySQL or Postgres are recommended**.

- <details>
         <summary><strong>What to learn:</strong></summary>
         <ol type='1'> 
          <li> Database Design </li>
          <li> Basic SQL Syntax (DDL & DML) </li>
          <li> Constraints </li>
          <li> Joins (<code>INNER JOIN & OUTER JOIN</code>) </li>
          <li> Aggregate Queries </li>
          <li> Views </li>
          <li> Built-In Functions </li>
          <li> Indexes (B+ Tree & Hash index) </li>
          <li> Transactions </li>
          <li> Pivot and Unpivot </li>
          <li> Window Functions </li>
         </ol>
    </details>
- <details>
         <summary><strong>Resources:</strong></summary>
         <ol> 
          <li> <a href='https://youtube.com/playlist?list=PLkpYqKNqc_CvjuJj9Tkic2F0R85BQsogs&si=5El61jCpMfcKLO2m'> Introduction to Databases (Ahmed Younes)</a><strong> (Recommended)</strong> Focuses on <strong>Database Design only</strong>.</li>
          <li>  <a href='https://youtu.be/kb-_GbpH3sQ?si=wz-fULzP2NMxLAKC'> SQL for Data Analysis | شاهد كيف أصبح الفيل والدرفيل أصدقاء (بالعربي Big Data)</a> Focuses on <strong>SQL</strong><i> - note: skip the installation part, Install MySql on your machine directly.</i> 
          </li>
          <li> 
            <a href='https://www.youtube.com/playlist?list=PLYpJKvLDuJhgMzOXRwUJ2_ZlVt3zSh8PA' target='_blank'> ITI SQL Server Arabic (ITI) </a>
          </li>
          <li> 
            <a href='https://www.youtube.com/playlist?list=PL4n1Qos4Tb6RP_OovpgjoHLkCVaYFy-aj'>[02] - Databases (MS. SQL Server) | قواعد البيانات (Metigator | عصام عبدالنبي)</a> you can skip it if you watch the previous video.
          </li>
          <li> 
            <a href='https://www.youtube.com/playlist?list=PLE8kQVoC67PzGwMMsSk3C8MvfAqcYjusF'>Relational Database Internals (TechVault)</a> 
          </li>
         </ol>
    </details>

### Master Programming Fundamentals & C# Syntax.

- <details>
               <summary><strong>What to learn:</strong></summary>
                    <ul>
                       <li> Basic Syntax & Data Types & Operators </li>
                       <li> If & Switch Statement</li>
                       <li> Rectangular & Jagged Arrays & Indices & Ranges </li>
                       <li> Strings & Verbatim String Literals (Parse, Formatting, Split, Join) </li>
                       <li> Switch Expression <i>(C# 8 or later)</i> </li>
                       <li> Type Casting & Boxing & Unboxing </li>
                       <li> Value Types & Reference Types (<code>ref & in & out</code>) </li>
                       <li> Foreach & iterators & yield </li>
                       <li> Compilation Process </li>
                       <li> Enums </li>
                       <li> Classes & Abstracted Class </li>
                       <li> Indexer & Operator Overload </li>
                       <li> Interfaces </li>
                       <li> IComparer vs IComparable  </li>
                       <li> Records (<code>record class</code> & <code>record struct</code>)</li>
                       <li> Pattern Matching With The Switch Statement <i>(C# 7 or later)</i></li>
                       <li> Delegate & Action & Func & Predicate </li>
                       <li> Events </li>
                       <li> Generics & Generic Delegate </li>
                       <li> 
                            <details>
                             <summary> C# Collection </summary>
                              <ol type="1">
                               <li> ArrayList </li> 
                               <li> Dictionary </li> 
                               <li> Tuple </li> 
                               <li> List </li> 
                               <li> LinkedList </li> 
                               <li> HashSet </li> 
                               <li> SortedSet </li> 
                              </ol>
                            </details> 
                       </li>
                       <li> 
                            <details>
                             <summary> Stream I/O </summary>
                              <ol type="1">
                               <li> Storage Stream (FileStream, MemoryStream and NetworkStream) </li> 
                               <li> Function Stream (CryptoStream, GZipStream, DeflateStream and AuthenticatedStream) </li> 
                               <li> Stream Helpers (StreamReader, StreamWriter, BinaryReader and BinaryWriter) </li> 
                              </ol>
                            </details> 
                       </li>
                       <li> <strong>LINQ (Language Integrated Query)</strong> <i>Take your time in this step please!</i></li>
                       <li> Span & Readonly Span </li>
                       <li> StringBuilder </li>
                       <li> Exceptions </li>
                       <li> Assemblies & Reflection </li>
                       <li> Threading </li>
                       <li> Asynchronous (<code>async</code>) </li>
                       <li> Serialization </li>
                    </ul>
        </details>
> [!Note]
> Explore these curated resources to deepen your understanding of specific topics (**you can choose one or more, or none at all!**):

- <details>
        <summary><strong> Resources:</strong></summary>
        <ol>
          <li> <a href='https://www.youtube.com/playlist?list=PL4n1Qos4Tb6SWPbJNpiznp-Ok4A8J_23l' target="_blank">[01] - Mastering C#.NET | احترف سي شارب (Metigator | عصام عبدالنبي) </a>
          <strong>(Recommended)</strong> Focuses on <strong> approximately 90% of fundamentals </strong> if you feel uncomfortable about this advanced playlist skip it right now.
          </li>
          <li>
             <a href='https://www.youtube.com/playlist?list=PLsV97AQt78NT0H8J71qe7edwRpAirfqOI' target="_blank"> C# Fundamentals (Passionate Coders | محمد المهدي) </a>Focuses on <strong>fundamentals</strong>.
          </li>
          <li>
             <a href='https://www.youtube.com/playlist?list=PLsV97AQt78NQYhO7NqlBTrJX_Nsk3SmyY' target="_blank"> C# Advanced (Passionate Coders | محمد المهدي) </a>Focuses on <strong>advanced topics</strong>.
          </li>
          <li>
             <a href='https://www.youtube.com/playlist?list=PL4n1Qos4Tb6Sj1Y4xJuJoWCuqleeG2yt6' target="_blank"> [03] - Language Integrated Query - LINQ | الاستعلامات المتكاملة (Metigator | عصام عبدالنبي) </a><strong>(Recommended) </strong>Focuses on <strong>LINQ</strong>.
          </li>
          <li>   <a href='https://www.geeksforgeeks.org/csharp-programming-language/?ref=lbp' target="_blank"> C# Tutorial (GFG)
          </a> </li>
          <li>   <a href='https://www.geeksforgeeks.org/c-sharp-params/' target="_blank"> C# | Params (GFG)
          </a> </li>
          <li>   <a href='https://www.geeksforgeeks.org/how-to-sort-an-array-in-c-sharp-array-sort-method-set-1/?ref=lbp' target="_blank"> How to sort an Array in C# | Array.Sort() Method Set – 1 (GFG)
          </a> </li>
          <li>   <a href='https://www.geeksforgeeks.org/c-sharp-verbatim-string-literal/?ref=lbp' target="_blank"> C# | Verbatim String Literal – @ (GFG)
          </a> </li>
          <li>   <a href='https://learn.microsoft.com/en-us/dotnet/standard/base-types/standard-numeric-format-strings' target="_blank"> Standard numeric format strings (Microsoft Docs)
          </a> </li>
          <li>   <a href='https://learn.microsoft.com/en-us/dotnet/standard/base-types/standard-date-and-time-format-strings' target="_blank"> Standard date and time format strings (Microsoft Docs)
          </a> </li>
          <li>   <a href='https://www.geeksforgeeks.org/anonymous-method-in-c-sharp/?ref=lbp' target="_blank"> Anonymous Method in C# (GFG)
          </a> </li>
          <li>   <a href='https://www.geeksforgeeks.org/c-sharp-multidimensional-indexers/?ref=lbp' target="_blank"> C# | Multidimensional Indexers (GFG)
          </a> </li>
          <li>   <a href='https://www.geeksforgeeks.org/collections-in-c-sharp/?ref=lbp' target="_blank">Collections in C# (GFG)
          </a> </li>
          <li>   <a href='https://drive.google.com/file/d/1qLaxdSzLAYByFLw_hylvtR17Y3PcnWEO/view?usp=sharing' target="_blank">C# 8 and .NET 8 (Mark J. Price)</a><strong> (Recommended)</strong> This book covers all topics except threading and async.
          </li>
        </ol>
  </details>

### Entity Framework Core

- <details>
             <summary><strong>What to learn:</strong></summary>
                  <ul>
                     <li> DbContext </li>
                     <li> Migrations </li>
                     <li> Entity Configuration (Fluent API & Annotations) </li>
                     <li> Relations </li>
                     <li> Queries & Updates </li>
                     <li> <details>
                          <summary> Inheritance Mapping Strategies </summary>
                          <ul>
                            <li> Table-per-hierarchy (TPH) </li> 
                            <li> Table-per-type (TPT) </li> 
                            <li> Table-per-concrete-type (TPC) </li> 
                          </ul>
                        </details>
                      </li>
                     <li> Indexes </li>
                     <li> Eager & Lazy & Explicit Loading </li>
                     <li> Interceptors </li>
                     <li> Transactions </li>
                  </ul>
      </details>

- <details>
        <summary><strong> Resources:</strong></summary>
                  <ul>
                    <li><a href='https://www.youtube.com/playlist?list=PL62tSREI9C-cHV28v-EqWinveTTAos8Pp' target="_blank"> [Arabic - بالعربي] Entity Framework Core (DevCreed)
          </a> </li>
                     <li>   <a href='https://www.youtube.com/playlist?list=PL4n1Qos4Tb6QZkbTWJx7wHqEABP8Pg6uv' target="_blank"> [05] - Data Access & EF-Core (Metigator | عصام عبدالنبي)
          </a> </li>
                  </ul>
      </details>

### ASP.NET Core MVC
- [Metigator](https://www.youtube.com/playlist?list=PL4n1Qos4Tb6S-uLNUmrgCJiQXfXi5KjRJ)
- [ITI Recordings - Eng/Christiene Zareef (Highly Recommended)](https://drive.google.com/drive/u/0/folders/1HZwQYm-ME578H8ANkv9w4167NDCRWecF?fbclid=IwAR1lCISZUSWI-3cMJC7Y22yCw0iMgn_0Ra2VuSVnLTCaBWV-13e-CFUbKNg)
- [Ahmed Mohamady](https://www.youtube.com/playlist?list=PLqPejUavRNTWqGYP-f1pHkbLYdbqi_Uhg)

### ASP.NET Core API
- [ITI Recordings - Eng Christine Zareef (Highly Recommended)](https://youtube.com/playlist?list=PLesfn4TAj57VzTrrGkOKWbNOOrUCdSQGo&si=IH-GyfrRzYhF-QXY)
- [Passionate Coders (Still recording)](https://www.youtube.com/playlist?list=PLsV97AQt78NQ8E7cEqovH0zLYRJgJahGh)

## Part 2: Extra

### API Secure with JWT Authentication
- [DevCreed](https://www.youtube.com/playlist?list=PL62tSREI9C-eYNE1Pyw0yv1tETs5V8WGd)

### SignalR for Real-Time Applications
- [ITI Recordings](https://www.youtube.com/playlist?list=PLesfn4TAj57WLtiWtHP1Xkel7WD6QHvpe)

### Microsoft Azure Cloud Services
- [ITI Recordings](https://youtube.com/playlist?list=PLesfn4TAj57WWPBzcEIGEfwzCPpw27-Lu&si=JjZf80QVb0XGxXAc)

### Software Containerization & Docker
- [Passionate Coders](https://www.youtube.com/playlist?list=PLsV97AQt78NTJTBGKI0GE3eJc2Q_SC2B-)
- [Codographia](https://www.youtube.com/playlist?list=PLX1bW_GeBRhCS2TJvGgu38P-Rf9aNXKZD)

# Remember

> [!important]
> This is a guide, adapt it to your pace, interests, and resources. With dedication and exploration, you'll conquer the C# and .NET landscape and create amazing things!

# Happy Learning!
