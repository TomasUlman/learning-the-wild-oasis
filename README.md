the-wild-oasis

⚠️ This is a study project based on a Udemy course. It is not intended for production use.
The README continues in Czech, as this project is part of my personal learning archive.

🏨 The Wild Oasis – interní dashboard pro správu „mini hotelu“

The Wild Oasis je komplexní React SPA aplikace sloužící jako interní administrační rozhraní pro správu ubytování, rezervací, uživatelů a statistik. Projekt používá Supabase jako backend (Auth, databáze, storage).

Aplikace obsahuje login, zabezpečené sekce, CRUD operace, nahrávání obrázků, filtrování, grafy a responzivní layout.

💡 Hlavní funkce

👤 Přihlášení a správa uživatelů

🛏️ Správa pokojů (cabins) – seznam, přidávání, úpravy, mazání

📖 Správa rezervací (bookings) – detail, check-in/out, změny statusu

📊 Dashboard se statistikami, grafy a metrikami

⚙️ Nastavení aplikace – profil, globální parametry

🌙 Dark / Light mód

🧭 Moderní UX – modály, toast notifikace, filtry, responzivita

🌐 Live demo

Funkční build je dostupný zde:

👉 https://tomasulman-the-wild-oasis.vercel.app/

Projekt běží na Supabase free verzi, která má automatické uspávání po týdnu neaktivity.
Pokud si chcete aplikaci projít v plně funkční podobě (login, data, CRUD), napište mi a backend případně aktivuji.

🛠 Použité technologie

React + Vite

React Router v6

TanStack React Query

Supabase (Auth, DB, Storage)

Styled Components

React Hook Form

Recharts

date-fns

Context API

ESLint

▶️ Jak si projekt prohlédnout

Kvůli napojení na privátní Supabase backend není možné projekt jednoduše spustit lokálně bez mých API klíčů.

Možnosti:

🔹 1) Chcete vidět funkční demo?

👉 Napište mi.
Supabase free verze backend uspává, ale já ho znovu aktivuji.

🔹 2) Chcete si jen prohlédnout kód?

Stačí repo stáhnout

🧠 Co jsem si na projektu vyzkoušel

Integraci Supabase (Auth, databáze, storage)

Pokročilou práci s daty přes React Query

Modulární architekturu po „features“

Izolované service vrstvy a vlastní hooky

Kompletní CRUD operace a admin dashboard

Statistické grafy, filtry a reporting

Řízení UI stavů (loading, error, optimistic updates)

🧼 Poznámka

Jeden z největších projektů kurzu — skvělý pro pochopení admin rozhraní, práce s daty, autentizací a moderního React stacku.
