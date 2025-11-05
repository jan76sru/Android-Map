# Android-Map
Understanding depth

Code Style guide :nail_care: - >  https://developer.android.com/kotlin/style-guide

### Philosophy 
Many iterations >>>> looking for perfections


# Kotlin + Android Concepts 

<table>
<tr>
<th>Kotlin Language Concepts</th>
<th>Android-Specific Concepts</th>
</tr>

<tr>
<td valign="top">

### 1. Language Fundamentals
- Variables: `val`, `var`
- Data types: Int, String, Boolean
- Operators: arithmetic, logical, range (`..`)
- Conditionals: `if`, `when`, loops
- String templates
- Smart casting

### 2. Functions & Functional Programming
- Default & named parameters
- Higher-order functions
- Lambdas
- Extension & inline functions
- Scope functions: `let`, `run`, `apply`, `also`, `with`

### 3. Classes & Object-Oriented
- Class declaration, constructors
- Inheritance (`open`, `override`)
- Interfaces, abstract classes
- Data, sealed, enum classes
- Singleton & companion objects
- Nested vs inner classes

### 4. Collections & Data Handling
- Lists, Sets, Maps
- Transformations: `map`, `filter`, `reduce`
- Sequences for lazy evaluation

### 5. Null Safety
- Nullable types (`String?`)
- Safe call (`?.`), Elvis (`?:`), non-null assertion (`!!`)
- `let`, `takeIf`, `takeUnless`

### 6. Coroutines & Concurrency
- `suspend` functions
- Builders: `launch`, `async`, `runBlocking`
- Dispatchers (`Main`, `IO`, `Default`)
- Structured concurrency
- `CoroutineScope`, `Job`, `SupervisorJob`

### 7. Generics & Type System
- Generic functions (`fun <T>`)
- Variance (`in`, `out`)
- Reified types, type aliases

### 8. Exception Handling
- `try`, `catch`, `finally`, `throw`
- Custom exceptions

### 9. Delegation & Advanced
- Property delegation (`by lazy`, `observable`)
- Interface delegation (`class A(b: B): I by b`)

### 10. Java Interoperability
- `@JvmStatic`, `@JvmOverloads`, `@JvmField`
- SAM conversion
- Handling Java nulls

</td>

<td valign="top">

### 11. Android Architecture
- Activity & Fragment lifecycle
- ViewModel for UI persistence
- LiveData / StateFlow
- Lifecycle-aware components
- Navigation component

### 12. Modern Android Patterns
- MVVM / MVI / Clean Architecture
- Repository pattern
- Dependency Injection (Hilt / Dagger)

### 13. UI Development
- XML layouts, ViewBinding, DataBinding
- Jetpack Compose:
  - `@Composable` functions
  - `remember`, `mutableStateOf`
  - `LaunchedEffect`, `SideEffect`
  - State management, `Scaffold`, `LazyColumn`
  - `Modifier` system
- Material theming (`MaterialTheme`, `Typography`)

### 14. Async & Reactive Flows
- Coroutines: `viewModelScope`, `lifecycleScope`
- Flow, StateFlow, SharedFlow
- `repeatOnLifecycle`
- Flow vs LiveData vs RxJava

### 15. Dependency Injection
- Hilt: `@AndroidEntryPoint`, `@Module`, `@Provides`, `@Inject`
- Scopes: `@Singleton`, `@ViewModelScoped`
- Component graph

### 16. Networking & Data
- Retrofit + OkHttp
- Gson / Moshi / Kotlinx.serialization
- Room (`@Entity`, `@Dao`, `@Query`)
- Repository for API + DB
- WorkManager for background jobs

### 17. Compose + Architecture
- State hoisting
- ViewModel + Compose integration
- `collectAsState()`
- `NavHost`, `NavController`

### 18. Testing
- Unit tests: JUnit, Mockito, Truth
- UI tests: Espresso, Compose Testing
- Coroutine testing (`TestDispatcher`, `runTest`)

### 19. Performance & Tools
- Memory management
- Lifecycle leak prevention
- Profilers: Memory, CPU, Network
- StrictMode, ANR watchdog
- Proguard & R8

### 20. Build System & CI/CD
- Gradle (plugins, build variants)
- Kotlin DSL (`build.gradle.kts`)
- Modularization
- CI integration (GitHub Actions, ADO)

### 21. Kotlin Multiplatform
- KMM (shared Android/iOS)
- `expect` / `actual`
- Shared networking & persistence

</td>
</tr>
</table>
