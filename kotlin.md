# 🧩 Android Jetpack Libraries (AndroidX)

> Jetpack is a collection of Android libraries that help developers build high-quality apps faster by following modern architecture practices and providing backward compatibility.

---

## ⚙️ Core & Base Libraries

<table>
<tr><th>Jetpack Component</th><th>Library</th><th>Description</th></tr>
<tr><td><b>AppCompat</b></td><td><code>androidx.appcompat:appcompat</code></td><td>Backward-compatibility support for modern UI components and Material theming.</td></tr>
<tr><td><b>Core KTX</b></td><td><code>androidx.core:core-ktx</code></td><td>Kotlin extensions for core Android framework APIs.</td></tr>
<tr><td><b>Annotations</b></td><td><code>androidx.annotation:annotation</code></td><td>Compile-time annotations to improve code correctness and lint checks.</td></tr>
<tr><td><b>MultiDex</b></td><td><code>androidx.multidex:multidex</code></td><td>Support for apps exceeding the 65K method limit (multiple DEX files).</td></tr>
<tr><td><b>Testing</b></td><td><code>androidx.test</code></td><td>Comprehensive testing framework for Android (JUnit, Espresso, UI tests, etc.).</td></tr>
</table>

---

## 🧱 Architecture & Data Components

<table>
<tr><th>Jetpack Component</th><th>Library</th><th>Description</th></tr>
<tr><td><b>Lifecycle</b></td><td><code>androidx.lifecycle:lifecycle-runtime</code></td><td>Manages Android components’ lifecycle awareness.</td></tr>
<tr><td><b>ViewModel</b></td><td><code>androidx.lifecycle:lifecycle-viewmodel</code></td><td>Holds and manages UI-related data lifecycle-consciously.</td></tr>
<tr><td><b>LiveData</b></td><td><code>androidx.lifecycle:lifecycle-livedata</code></td><td>Observable lifecycle-aware data holder for reactive UIs.</td></tr>
<tr><td><b>Room</b></td><td><code>androidx.room:room-runtime</code></td><td>SQLite object mapping library for local persistence.</td></tr>
<tr><td><b>Paging</b></td><td><code>androidx.paging:paging-runtime</code></td><td>Loads and displays large data sets gradually, page by page.</td></tr>
<tr><td><b>Navigation</b></td><td><code>androidx.navigation:navigation-fragment</code></td><td>In-app navigation between destinations using fragments.</td></tr>
<tr><td><b>Navigation UI</b></td><td><code>androidx.navigation:navigation-ui</code></td><td>UI helpers for Navigation (e.g., toolbar and drawer integration).</td></tr>
<tr><td><b>WorkManager</b></td><td><code>androidx.work:work-runtime</code></td><td>Schedules deferrable, guaranteed background work.</td></tr>
</table>

---

## 🎨 User Interface Components

<table>
<tr><th>Jetpack Component</th><th>Library</th><th>Description</th></tr>
<tr><td><b>ConstraintLayout</b></td><td><code>androidx.constraintlayout:constraintlayout</code></td><td>Powerful layout manager for flexible UI positioning.</td></tr>
<tr><td><b>RecyclerView</b></td><td><code>androidx.recyclerview:recyclerview</code></td><td>Displays large data sets efficiently using ViewHolders.</td></tr>
<tr><td><b>CardView</b></td><td><code>androidx.cardview:cardview</code></td><td>Container view that provides consistent Material card styling.</td></tr>
<tr><td><b>ViewPager2</b></td><td><code>androidx.viewpager2:viewpager2</code></td><td>Modern version of ViewPager built on RecyclerView.</td></tr>
<tr><td><b>WebKit</b></td><td><code>androidx.webkit:webkit</code></td><td>Helpers and compatibility APIs for working with WebView.</td></tr>
<tr><td><b>Material Components</b></td><td><code>com.google.android.material:material</code></td><td>Official Material Design widgets, styles, and themes for Android.</td></tr>
</table>

---

## 🪄 Jetpack Compose (Modern UI Toolkit)

<table>
<tr><th>Jetpack Component</th><th>Library</th><th>Description</th></tr>
<tr><td><b>Compose UI</b></td><td><code>androidx.compose.ui:ui</code></td><td>Core UI elements and rendering system for Jetpack Compose.</td></tr>
<tr><td><b>Compose Foundation</b></td><td><code>androidx.compose.foundation:foundation</code></td><td>Basic building blocks and layout primitives for Compose UI.</td></tr>
<tr><td><b>Compose Animation</b></td><td><code>androidx.compose.animation:animation</code></td><td>Declarative animation APIs for Compose.</td></tr>
<tr><td><b>Compose Material 2</b></td><td><code>androidx.compose.material:material</code></td><td>Material Design 2 components built with Compose.</td></tr>
<tr><td><b>Compose Material 3</b></td><td><code>androidx.compose.material3:material3</code></td><td>Material You (Material Design 3) components for Compose.</td></tr>
<tr><td><b>Compose Runtime</b></td><td><code>androidx.compose.runtime:runtime</code></td><td>Core Compose runtime and state management system.</td></tr>
<tr><td><b>Navigation Compose</b></td><td><code>androidx.navigation:navigation-compose</code></td><td>Navigation integration for Compose applications.</td></tr>
</table>

---

## 📱 Device & Platform-Specific Libraries

<table>
<tr><th>Jetpack Component</th><th>Library</th><th>Description</th></tr>
<tr><td><b>CameraX Core</b></td><td><code>androidx.camera:camera-core</code></td><td>Core APIs for CameraX functionality and image capture.</td></tr>
<tr><td><b>CameraX Lifecycle</b></td><td><code>androidx.camera:camera-lifecycle</code></td><td>Lifecycle-aware camera binding for Activity/Fragment.</td></tr>
<tr><td><b>CameraX View</b></td><td><code>androidx.camera:camera-view</code></td><td>Prebuilt camera preview and controls.</td></tr>
<tr><td><b>Wear OS Core</b></td><td><code>androidx.wear:wear</code></td><td>APIs for building apps on Wear OS devices.</td></tr>
<tr><td><b>Wear OS Tiles</b></td><td><code>androidx.wear.tiles:tiles</code></td><td>APIs to build custom tiles for Wear OS watches.</td></tr>
<tr><td><b>Window Manager</b></td><td><code>androidx.window:window</code></td><td>APIs for foldable, multi-window, and large-screen devices.</td></tr>
</table>

---

## 🧩 Kotlin Extensions (KTX)

<table>
<tr><th>Jetpack Component</th><th>Library</th><th>Description</th></tr>
<tr><td><b>Core KTX</b></td><td><code>androidx.core:core-ktx</code></td><td>Idiomatic Kotlin extensions for Android APIs.</td></tr>
<tr><td><b>Fragment KTX</b></td><td><code>androidx.fragment:fragment-ktx</code></td><td>Kotlin extensions that simplify Fragment operations.</td></tr>
<tr><td><b>ViewModel KTX</b></td><td><code>androidx.lifecycle:lifecycle-viewmodel-ktx</code></td><td>Coroutine support for ViewModel.</td></tr>
<tr><td><b>Navigation KTX</b></td><td><code>androidx.navigation:navigation-fragment-ktx</code></td><td>Kotlin-friendly Navigation component helpers.</td></tr>
<tr><td><b>WorkManager KTX</b></td><td><code>androidx.work:work-runtime-ktx</code></td><td>Coroutine support for WorkManager background tasks.</td></tr>
</table>

---

## 🔍 References

<table>
<tr><th>Resource</th><th>Link</th></tr>
<tr><td>Android Jetpack Overview</td><td><a href="https://developer.android.com/jetpack">developer.android.com/jetpack</a></td></tr>
<tr><td>AndroidX Library Explorer</td><td><a href="https://developer.android.com/jetpack/androidx/explorer">developer.android.com/jetpack/androidx/explorer</a></td></tr>
<tr><td>AndroidX GitHub Repository</td><td><a href="https://github.com/androidx/androidx">github.com/androidx/androidx</a></td></tr>
</table>
