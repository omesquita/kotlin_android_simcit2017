# Minicurso Iniciando com Kotlin no Android

Lib Anko Kotlin
https://github.com/Kotlin/anko

### Dependências utilizadas
- Anko Kotlin
implementation 'org.jetbrains.anko:anko-commons:0.10.2'
- RecyclerView + CardView
implementation 'com.android.support:recyclerview-v7:26.1.0'
implementation 'com.android.support:cardview-v7:26.1.0'



allprojects {
    repositories {
        jcenter()
        maven { url 'https://maven.google.com' }
    }
}

https://developer.android.com/topic/libraries/architecture/room.html
### ROOM PERSISTENCE
implementation "android.arch.persistence.room:runtime:1.0.0-rc1"
annotationProcessor "android.arch.persistence.room:compiler:1.0.0-rc1"
kapt "android.arch.persistence.room:compiler:1.0.0-rc1"
