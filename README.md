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
classDef red fill:red,stroke:#000,stroke-width:2px,color:#fff
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
            B4(Java - Unit Test Junit,Mockito,AssertJ)     
            B1-->B2-->B3-->B4           
        end
      
    B4--->B5
        
        subgraph "B 2" 
            B5(Layered Architecture)
            B6(DIP-principle, IoC Container-framework)
            B7(Spring Core)
            B8(RESTful API Design)                       
            B9(Spring WebMVC)
            B10(Spring Boot):::red
            B11(Spring Boot Test) 
            B12(Spring Boot JPA)
            
            B5-->B6-->|제어역전-객체관리, 종속주입-고차원 관리|B7
            B7-->B8-->|Resource,Http Method,Stateless,Cacheable,Uri|B9-->B10-->B12
            B10-->B11
                        
        end        
    end
    
    G-->F1
    
    subgraph "Front end"
        subgraph "F 1"
            F1(HTML)
            F2(CSS)
            F3(JavaScript - Part 1)            
            F4(JavaScript - Part 2)            
            F6(TypeScript)                        
            F3-->|콜백,Promise,AWAIT,ASYNC|F4
            F1-->F2-->F3-->|체이닝,Promise API|F4-->F6
        end
    
    F6 ---> F7   
        
        subgraph "F 2"
            F7(React Web Framework):::red    
            F8(JavaScript - Unit Test)            
        end       
    end
    F7 -->F8
    F7 -->|hooks,fetch,event,rendering,redux,router,token|P1
    B12 --> P1
         
    B4<-..->|TEST|F8
    B4<-..->|TEST|B11
           
    subgraph "Project"
            P1(Toy Project)
            P2(Domain Driven Design)            
            P3(Application Modernization Project):::orange        
    end 
    
    subgraph "Microservice"
            P21(Application Layer)
            P22(Domain Model Layer):::orange
            P23(Infrastructure Layer)
            P21-->P23
            P23-->P22
            P21-->P22
    end
    
    P22-..-P2
    
    P1-->P2-->P3



```

```mermaid
flowchart LR

classDef blue fill:blue,stroke:#000,stroke-width:2px,color:#fff

    principle>Principle 원칙]:::blue---A[IoC - inversion of Control]-->E[제어는 컨테이너,프레임워크가 담당해야 한다.]
    principle---B[DIP - Dependency Inversion Principle ]-->F[저수준 모듈이 고수준 모듈에 의존해야 한다.]
    pattern>Pattern 방법]:::blue---C[DI - Dependency Injection]-.-G1[*Constructor Injection*]
    C-.-G2[Setter Injection]
    C-.-G3[Method Injection]
    framework>Framework]:::blue---D[IoC Container]-->|has|H[오프젝트 빈]
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
