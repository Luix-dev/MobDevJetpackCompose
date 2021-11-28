# MobDevJetpackCompose
This is an exercise from Digital Ideation Master - Mobile Development

## Questions 
* Was ist eine Composable Function?

_Funktioniert wie eine normale Funktion. Wird aber mit **@Composable** annotiert. Dadurch kann die Funktion andere @Composable Funktionen aufrufen --> Kann mit einem Input ein Stück UI generieren._

---

* Wie erzeugen wir eine Container Function? Was ist deren Zweck?

_Es wird ein Composable Element erzeugt, welches z.B eine Unit als Parameter nimmt. So können allen Children ein Design übergeben oder ein Wert übergeben werden._

---

* Erläutern Sie in eigenen Worten, was im Kontext von Jetpack Compose "Source of truth" und State goisting" bedeuten.

_States von Funktionien, die von mehreren anderen Funktionen gelesen oder geändert werden, brauchen "leben" in einer geteilten Umgebung. Dieses Prozess heisst "state hoisting". Einen state "hoistable" machen verhindert, das es Duplikationen oder Bugs gibt. Die "source of truth" gehört immer dem, der den State kontrolliert._

---
