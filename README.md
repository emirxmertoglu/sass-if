# SASS'ta Akış Kontrolü

## @if

SASS'ta if koşulunun yazılma şekli aşağıdaki gibidir. Bu ifade **true** ya da **false** değer döndürür.

```scss
@if <koşul> {
    ...
}
```

## @else

Bir if koşulunu **isteğe bağlı** olarak else koşulu takip edebilir. Eğer if bloğundan **false değeri dönerse** else bloğu değerlendirilir. Yazımı aşağıdaki gibidir.

```scss
@if <koşul> {
    ...
} @else {
    ...
}
```

## @else if

Eğer if bloğundan **false değeri dönerse** else if bloğuna bakılır. else if bloğundan **true** değeri dönene kadar diğer else if bloklarına bakılır, bu arada istediğimiz kadar else if bloğu yazabiliriz, eğer hiç bir else if bloğundan true değeri dönmezse else bloğundaki default değer döner. Yazımı aşağıdaki gibidir.

```scss
@if <koşul> {
    ...
} @else if <koşul> {
    ...
} @else if <koşul> {
    ...
} @else if <koşul> {
    ...
} @else {
    ...
}
```
