# C# and .Net Roadmap

# Summary

This roadmap guides your journey through the exciting world of C# and .NET development, catering to both beginners and experienced programmers. It provides a structured path for learning and progression, outlining key topics and resources.

# Part 1: Learning Your Way Up

## Foundation (Beginner)

- Master programming fundamentals & C# syntax.

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
                   <li> Records </li>
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


- Explore the .NET and CLI tools.

## Building Applications (Intermediate)

- Dive into web development with ASP.NET.
  - Resources: Microsoft's ASP.NET documentation, Pluralsight's ASP.NET Core Learning Path
- Tame databases using SQL and Entity Framework.
  - Resources: W3Schools SQL Tutorial, Microsoft's Entity Framework Core documentation
- Write robust tests and deploy your creations.
  - Resources: Microsoft's Unit Testing documentation, xUnit.net documentation, Microsoft's ASP.NET deployment documentation

## Advanced Topics (Experienced)

- Explore cloud-native development with Azure.
  - Resources: Microsoft's Azure documentation, .NET for Cloud-Native Development book
- Design microservices and APIs.
  - Resources: Building Microservices by Sam Newman, Microsoft's ASP.NET Core Web API documentation
- Leverage Machine Learning and AI.
  - Resources: Microsoft's ML.NET documentation, Azure Cognitive Services documentation
- Build cross-platform applications with Xamarin or MAUI.
  - Resources: Microsoft's Xamarin documentation, .NET MAUI documentation

# Part 2: Fueling Your Growth

- **Community:** Engage with the active C# and .NET community (forums, GitHub, Discord).
- **Personal Projects:** Build meaningful projects to solidify your learning.
- **Stay Updated:** Keep track of the latest advancements.
- **Documentation:** Leverage comprehensive resources for support (Microsoft's documentation for C# and .NET).

# Remember

> [!important]
> This is a guide, adapt it to your pace, interests, and resources. With dedication and exploration, you'll conquer the C# and .NET landscape and create amazing things!

# Happy Learning!
