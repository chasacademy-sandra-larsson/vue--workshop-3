
# Vue #3: Vue Router + Fetcha data i lifecycle hook

👋 Se föreläsningen från i onsdags denna vecka  ✅ 

**Syftet med denna workshop:** 

* Använda grunderna i Vue router 
* Fetcha data i lifecycle Hook

Dokumentation för Vue Router: [https://router.vuejs.org/](https://router.vuejs.org/)

Använd dig av orginaldokumentationen [https://vuejs.org/](https://vuejs.org/). Du hittar även bra pedagogiskt material på Vue Mastery [https://www.vuemastery.com/](https://www.vuemastery.com/)

Bra lathund från Vue Mastery [https://www.vuemastery.com/vue-cheat-sheet/](https://www.vuemastery.com/vue-cheat-sheet/)


# 👩🏽‍💻 Övning 1: Setup av Vue Router för att navigera mellan olika views

Använd dig av [Vue Mastery Cheat Sheet for Basic Routing](https://storage.googleapis.com/vue-mastery.appspot.com/flamelink/media/Vue-Router-Cheat-Sheet.pdf?GoogleAccessId=firebase-adminsdk-jyioc%40vue-mastery.iam.gserviceaccount.com&Expires=16725225600&Signature=sQMP0BSwCpYgLovvlojzWUBxRG3QGnq6qwcFfAeT4h3mFKSh%2B38P5oSUnxDKdsCxsgGnsHaOUqapaEw%2FukuXSCf6H6jA4Pb14ajGWTISWxP2E6VaKfTQ9jz8B4AY0GiFJlIrEE1x3njfQgF7IoUMaeJdddFU3ZJ3CNiuvcvk5IM0DKDFU0exMK0xJZIqnUtb9iWbihcJrZaY5hb4JBiGzooDX%2BgXzaUZzIINNsHyrVRk%2FMKWCGlezR%2FIewZ1YXIiGT5RPau6kGK%2BxTs7K3Rgf2%2Bcm%2BYkyfz3Ai87gfM%2BoKY5m%2FDq8sn7%2BsdMoquHP2NWncox8sR1mogWAEM8uzJDbQ%3D%3D) eller annan dokumentation där du sätter upp enkel routing i en Vueapp. 

Appen ska kunna navigera mellan en HomeView (/), en AboutView (/about) samt något annat valbart (Movies/Users/Products). 

Bassidan ska vara i App.vue med en Header där man kan navigera mellan dessa views samt en Main där <router-view/> visar aktuell view/component.

# 👩🏽‍💻 Övning 2: Fetcha data + dynamisk routing

Använd dig av [JSON Server](https://github.com/typicode/json-server) för att använda en "mock" av ett REST API. Definera din data i json-filen med en eller flera resurser. Du väljer typ av resurs/-er själv :-(

Fetcha en lista av data i en komponent (SomeList.vue) och rendera listan. En användare ska kunna klicka på ett listobjekt och då komma till SomeDetails.vue som visar detailjer om listobjektet. Här använder du dig av dynamisk routing 'some-resource/:id'. SomeDetails.vue ska alltså fetcha enbart baserat på id:t.

Hur fetchar man i Vue? Läs på om Lifecycle Hooks! En del fetchar datat i mounted() och en del i createt(). Läs på om skillnaderna.

Här kan du läsa om [Lifecycle Hooke i Vue.](https://vuejs.org/guide/essentials/lifecycle.html)



# ✅ Redovisning:
* Du redovisar minst uppgiften för övningen. 
* ***Om du inte kan delta på workshopen, redovisar du ovanstående nästkommande workshop***







