## Panduan Nulis Blog di Parsinta

Jika Anda mengetahui bagaimana menggunakan [markdown](https://www.markdownguide.org/cheat-sheet/), maka basic nya akan sudah dapat. Jika Anda tidak mengetahuinya, maka contoh ini akan membuat Anda mengerti.

Berikut adalah contoh-contoh pembuatan artikel di Parsinta.

> Anda bisa langsung melihat hasil dari contoh ini [Panduan Menulis Artikel di Parsinta](https://parsinta.com/articles/panduan-menulis-artikel-di-parsinta-5i3r0#content-tabel).

## Code

Untuk membuat kode, bisa dengan menggunakan backtick 3x dengan bahasa nya.

### Codeblock

Untuk PHP bisa dengan

```php
class User
{
		
}
```

### Codeblock dengan Filename

Jika ingin membuat nama file, bisa dengan seperti:

```php filename=app/Model/User.php
use App\Models\Model;

class User extends Model
{
		
}
```

Itu adalah contoh untuk PHP, jika Anda ingin menggunakan javascript, maka bisa dibuat `js`, `jsx`, `tsx`, `css`, `html` dan seterusnya.

Untuk blade, bisa digunakan `html` saja. Untuk terminal, bisa memakai `bash`, begini contohnya:

```bash
composer global require laravel/installer
```

Menampilkan json misalnya

```json
[
    {
        "id": 86,
        "title": "UI Laravel dan React",
        "url": "http://parsinta.test/series/ui-laravel-dan-react-nqp6j",
        "type": "series"
    },
    {
        "id": 85,
        "title": "Laravel Precognition",
        "url": "http://parsinta.test/series/laravel-precognition-faupv",
        "type": "series"
    },
]
```

Atau mungkin typescript.

```tsx
import { ReactNode } from 'react';
import { Head } from '@inertiajs/react';
import Footer from '@/layouts/footer';
import Navbar from '@/layouts/navbar';
import { Toaster } from '@/components/toaster';
import FlashMessage from '@/components/flash-message';

type Props = { title?: string; children: ReactNode };
export default function AppLayout({ title, children }: Props) {
    return (
        <>
            <Head title={title} />
            <FlashMessage />
            <Toaster />
            <Navbar />
            {children}
            <Footer />
        </>
    );
}
```

Atau mungkin dengan `jsx`:

```jsx filename=./layouts/app-layout.jsx
import { ThemeProvider } from '@/components/theme-provider';
import { Navbar } from '@/components/navbar';
export function AppLayout({ children }) {
    return (
        <ThemeProvider defaultTheme= 'dark' storageKey = 'vite-ui-theme' >
            <Navbar />
            { children }
        </ThemeProvider>
    );
}
```

Contoh html

```html filename=src/index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

## Callout

Terbagi 3, yaitu `**warning**`, `**note**` dan `**twitter**`. Twitter masih beta, yang sering saat ini dipakai adalah `warning` dan `note`

### Cara pakai Warning

Jika Anda ingin memberi semacam peringatan, bisa langsung menggunakan tanda `>` diikuti dengan `**warning**`.

Berikut contoh nya

> **warning**
> Isi peringatan yang ingin dibuat


Butuh beberapa paragraph bisa langsung seperti ini:

> **warning**
> Paragraph 1
>
> Paragraph 2


### Cara pakai Note

Jika Anda ingin memberi semacam peringatan, bisa langsung menggunakan tanda `>` diikuti dengan `**note**`.

Berikut contoh nya

> **note**
> Isi peringatan yang ingin dibuat


Butuh beberapa paragraph bisa langsung seperti ini:

> **note**
> Paragraph 1
>
> Paragraph 2



## Attribute

### Link

Jika Anda ingin membuat link, simpel saja dengan cara [Parsinta](https://parsinta.com/).

### Youtube Embed
Berikut adalah contoh embed video dari youtube Parsinta.
[Volt untuk Laravel Livewire](https://youtu.be/CcH_gF6QLxU)

### Tabel

| Metode     | Deskripsi                                                    |
| ---------- | ------------------------------------------------------------ |
| **GET**    | Meminta informasi, seperti mengambil foto dari server.       |
| **POST**   | Mengirimkan informasi baru, misalnya mengirim pesan di media sosial. |
| **PUT**    | Memperbarui informasi yang sudah ada, seperti mengubah judul foto. |
| **DELETE** | Menghapus sesuatu, seperti menghapus komentar pada suatu postingan. |
| **PATCH**  | Mengubah sebagian dari informasi, misalnya memperbarui sebagian dari data pengguna. |

### Daftar Isi

Daftar isi akan otomatis di generasi dari h2,h3,h4 yang Anda buat.

## Penulisan Lengkap

Di dalam setiap jalinan *huruf*, tersembunyi kekuatan untuk mengubah  dunia. Menulis adalah cara untuk memberi suaramu **makna yang abadi**.  Jadilah arsitek kalimat, penjaga cerita, dan penjelajah ide. Tak perlu  ragu, biarkan imajinasimu menjelma menjadi kata-kata. 

Dengan menulis,  kita tak hanya menyampaikan `informasi`, tetapi juga menginspirasi,  menghubungkan, dan merayakan kompleksitas kehidupan. Mari mulai  sekarang, karena setiap kata yang tergores adalah langkah menuju  keabadian.



## Kesimpulan

Tuliskan ceritamu dan biarkan kata-kata merajut duniamu. Setiap tulisan  adalah jendela jiwa yang mengajak orang lain mengenalmu. 

Mari  bersama-sama mewujudkan ide, inspirasi, dan pemikiran menjadi  kalimat-kalimat indah yang menginspirasi. Dunia menantimu untuk  berbicara melalui tulisan. Mulailah menulis hari ini dan biarkan  kata-katamu mengalir seperti sungai kreativitas yang tiada henti!
