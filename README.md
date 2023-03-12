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
            B4(Java - Unit Test)     
            B401([Junit,Mockito,AssertJ])   
            B1-->B2-->B3-->B4
           
        end
      
    B4---|Important|B401--->B5
        
        subgraph "B 2" 
            B5(Layered Architecture)
            B6(DIP, IoC Container)
            B7(RESTful API Design)
            B8(Spring Core)
            B9(Spring Boot):::red 
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
            F301([프라미스,AWAIT,ASYNC])
            F4(JavaScript - Part 2)
            F5(JavaScript - Unit Test)
            F6(TypeScript)
            F1-->F2-->F3-->F4-->F5-->F6            
            F3---|Important|F301--->F4
        end
    
    F6 ---> F7   
        
        subgraph "F 2"
            F7(React Web Framework):::red                
        end       
    end
    
    F7 --> P1
    B10 --> P1
    P1 ---> P2
    
    B4<-..->|BOTH TEST|F5
    
    subgraph "Project"
            P1(Toy Project)
            P2(AM Project):::orange        
    end 





```

```mermaid
flowchart LR

classDef blue fill:blue,stroke:#000,stroke-width:2px,color:#fff

    principle>Principle 원칙]:::blue---A[IoC - inversion of Control]-->E[제어는 컨테이너,프레임워크가 담당해야 한다.]
    principle---B[DIP - Dependency Inversion Principle ]-->F[저수준 모듈이 고수준 모듈에 의존해야 한다.]
    pattern>Pattern 방법]:::blue---C[DI - Dependency Injection]-.-G1[Constructor Injection]
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
