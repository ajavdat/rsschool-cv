# Abrorov Javdat

## Contact info

- e-mail: [javdat.abrorov[at]gmail.com](mailto:javdat.abrorov@gmail.com)
- telegram: [@javdat](https://t.me/javdat)

## Summary

A team player who constantly works on himself and loves to learn new technologies that lead the business to new heights

## Skills

- C#
- ASP.NET
- T-SQL
- JavaScript
- TypeScript
- NodeJS
- MongoDB
- HTML
- CSS
- GIT

## Code examples

```csharp
class HtmlLoader
    {
        private readonly HttpClient _client;
        private readonly string _url;

        public HtmlLoader(IParserSettings settings)
        {
            _client = new HttpClient();
            _url = settings.BaseUrl;
        }

        public async Task<string> GetSource(string searchQuery)
        {
            var urlWithQuery = string.Concat(_url, searchQuery);
            var response = await _client.GetAsync(urlWithQuery);
            string source = null;

            if (response != null && response.StatusCode == HttpStatusCode.OK)
            {
                source = await response.Content.ReadAsStringAsync();
            }

            return source;
        }
    }
```

## Experience

- application refactoring
- sql query optimization
- integration of EDMS with 1C Accounting
- synchronization with Active Directory
- create various reports for customers
- creation of procedures and T-SQL scripts in the database
- internal micro-services development

## Education

**2015 - 2017: Tashkent University of Information Technologies**

_Master of Science: Software Design and Architecture_

## Languages

- Uzbek: Native
- English: B2 — Upper Intermediate
- Russian: C2 — Proficiency
