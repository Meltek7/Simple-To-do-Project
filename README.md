# To-Do List Application

Bu proje, [Motoko](https://sdk.dfinity.org/docs/developers-guide/motoko/overview.html) programlama dili ile yazılmış basit bir To-Do list uygulamasıdır. Kullanıcılar görevler ekleyebilir, tamamlayabilir ve tamamlanmış görevleri temizleyebilirler.

## Özellikler

- Görev ekleme
- Görevleri tamamlama
- Tamamlanan görevleri temizleme
- Tüm görevleri listeleme

## Kullanım

### Başlatma

Uygulamayı başlatmak için Motoko SDK'sını kurmanız gerekmektedir. Aşağıdaki adımları izleyin:

1. Motoko SDK'sını indirin ve kurun.
2. Proje dosyasını klonlayın veya indirin.
3. Proje dizinine gidin ve aşağıdaki komutu çalıştırarak uygulamayı başlatın:

API
- addTodo(description: Text) : async Nat
Açıklama: Yeni bir görev ekler.
Parametre:
description: Görev açıklaması (Text).
Dönüş Değeri: Eklenen görevin kimliği (Nat).
- getTodos() : async [ToDo]
Açıklama: Tüm görevleri döner.
Dönüş Değeri: Görevlerin bir listesi ([ToDo]).
- completeTodo(id: Nat) : async ()
Açıklama: Belirtilen görevi tamamlar.
Parametre:
id: Tamamlanacak görevin kimliği (Nat).
- showTodos() : async Text
Açıklama: Tüm görevleri kullanıcıya gösterir.
Dönüş Değeri: Görevlerin metin olarak listesi (Text).
- clearCompleted() : async ()
Açıklama: Tamamlanan görevleri temizler.

## Geliştirici Bilgileri
Bu projeyi geliştiren Meltem ile iletişime geçmek için aşağıdaki bilgileri kullanabilirsiniz:

E-posta: meltemtekeli7@gmail.com
GitHub: github.com/Meltek7

## Lisans
Bu proje MIT lisansı altındadır. Daha fazla bilgi için LICENSE dosyasını kontrol edin.
