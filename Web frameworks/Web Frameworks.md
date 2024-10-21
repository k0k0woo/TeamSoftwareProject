
### Backend
#backend

C#
- [[ASP.Net core]]

GO 
- [[Fiber]]

Rust
- [[Rocket]]
- [[Axum]]

JavaScript
- [[Node JS]]

PHP
- [[Larvel]]

Python
- [[Flask]]
- [[Django]]
### Frontend
#frontend

JavaScript / Typescript
- [[React JS]]
- [[Solid JS]]
- [[Angular JS]]

C#
- [[Blazor]]



### Backend Performance

Using data from https://web-frameworks-benchmark.netlify.app/result?asc=0&f=fiber,fasthttp,aspnet-minimal-api,rocket,axum,blaze-node,laravel,flask,django&metric=totalRequestsPerS&order_by=level64

| Rank | Framework    | Requests / Second (rounded) |
| ---- | ------------ | --------------------------- |
| 1    | fibre        | 457,000                     |
| 2    | axum         | 373,000                     |
| 3    | asp.net core | 352,000                     |
| 4    | rocket       | 290,000                     |
| 5    | node js      | 192,000                     |
| 6    | larvel       | 7,900                       |
| 7    | flask        | 2,900                       |
| 8    | django       | 2,800                       |


## Suggestions


| rank | backend          | frontend     | Docs                                                                                                    | summary                                                                                                     |
| ---- | ---------------- | ------------ | ------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| 1    | [[ASP.Net core]] | [[Blazor]]   | https://learn.microsoft.com/en-gb/aspnet/core/blazor/?view=aspnetcore-8.0&WT.mc_id=dotnet-35129-website | Good support, Full Stack C#, super easy setup and database support in visual studio, Still good performance |
| 2    | Go-[[Fiber]]     | [[React JS]] | Fiber - https://gofiber.io/                    React-https://react.dev/                                 | Super high performance, not as easy to learn,                                                               |
| 3    | [[Node JS]]      | [[React JS]] | Node-https://nodejs.org/docs/latest/api/ React-https://react.dev/                                       | retains ease of setup and low learning curve, low backend performance, Full stack JavaScript.               |

All have full compatibility with all main browsers (Google Chrome, Edge, Firefox, Safari ….)
