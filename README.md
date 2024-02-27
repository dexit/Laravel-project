# Laravel-project
Teorija:
    • Kas ir API?
    1. API (Application Programming Interface) ir saskarne starp dažādām programmatūras komponentēm, kas nosaka, kā tās var mijiedarboties un izmantot viena otru.
    
    • Kā deklarēt mainīgo PHP valodā?
    2. PHP valodā mainīgo deklarē ar `$` simbolu, piemēram: `$mainigais = "Vērtība";`
    
    • Kādu arhitektūru izmanto Laravel, paskaidro kā tā strādā:
    3. Laravel izmanto Model-View-Controller (MVC) arhitektūru. Model pārvalda datubāzi (izmantojot Eloquent ORM), View attēlo lietotājam informāciju, un Controller apstrādā lietotāja pieprasījumus un sazinās ar Model un View.
    
    • Kas ir ORM, kāpēc to izmanto tīra SQL vietā?
    4. ORM (Object-Relational Mapping) ir tehnoloģija, kas ļauj attēlot datubāzes ierakstus kā objektus, tādējādi atvieglojot darbu ar datubāzi. To izmanto tīra SQL vietā, lai samazinātu kodu un uzlabotu saprotamību.
    
    • Uzraksti Eloquent ORM pieprasījumu modelim User, kur nepieciešams iegūt visus lietotājus kuriem reitings ir lielāks par 4. Lietotāju tabulas struktūra:
    5. Eloquent ORM pieprasījums, lai iegūtu visus lietotājus ar reitingu lielāku par 4, izskatītos šādi:
    $lietotaji = User::where('rating', '>', 4)->get();
