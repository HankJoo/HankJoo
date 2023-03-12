>#### 저는요.
***
| 항목 | 내용 |
| :---: | --- |
| 한글 | ***한규*** |
| 영문 | ***Hank*** |
***

```mermaid
flowchart TB

%% Colors %%
classDef blue fill:blue,stroke:#000,stroke-width:2px,color:#fff
classDef orange fill:orange,stroke:#000,stroke-width:2px,color:#fff
      
    subgraph BASIC                          
        D(Dev Environment):::blue
        M(Markdown)
        G(Git)
        D-->M-->G                                             
    end
    
    G-->B1      
                    
    subgraph "Backend"
        subgraph "B 1"
            B1(Java - Basic)
            B2(Java - SOLID)
            B3(Java - ETC)        
            B4(Java - Unit Test)        
            B1-->B2-->B3-->B4
        end
    
    B4-->B5
        
        subgraph "B 2" 
            B5(Layered Architecture)
            B6(DIP, IoC Container)
            B7(RESTful API Design)
            B8(Spring Core)
            B9(Spring Boot)
            B10(Spring WebMVC)
            B5-->B6-->B7-->B8-->B9-->B10
        end        
    end
    
    G-->F1
    
    subgraph "Front end"
        subgraph "F 1"
            F1(HTML)
            F2(CSS)
            F3(JavaScript - Part 1)
            F4(JavaScript - Part 2)
            F5(JavaScript - Unit Test)
            F6(TypeScript)
            F1-->F2-->F3-->F4-->F5-->F6
        end
    
    F6 --> F7   
        
        subgraph "F 2"
            F7(React)                
        end       
    end
    
    F7 --> P1
    B10 --> P1
    P1 --> P2
    
    B4---F5
    
    subgraph "Project"
            P1(Toy Project)
            P2(AM Project):::orange        
    end 




```

>#### 프로그래밍 경험

> ``console.log("Hello World!");``
> - C#.NET ASP.NET JAVA Android SOAP WCF REST 
> - HTML CSS JAVASCRIPT REACT NEXT.JS NODE.JS PRISMA(ORM)
> - ORACLE MSSQL MYSQL POSTGRESQL  
> - VS CODE, Studio
***
>#### 새로운 경험..

> - Markdown GIT 
> - TYPESCRIPT SPRING BOOT
> - JEST Junit Mockito AssertJ
> - Linux Ubuntu
> - IntelliJ World.  
> - Mermaid
***



>#### 하고 싶은 말

> - 내 주변의 모든 분들이 스승이다.
> - 자신감을 갖자. 
> - 노력하면 언젠간 된다.
> - 아직(?) 젋다.
> - MACBOOK이 없다. 언제 나올라나. 낙오하면 안되는데...

>#### 지금 목표

> - 매일 Github에서 녹색불 붙이기!!!

<wink586@naver.com>
