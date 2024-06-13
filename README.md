# flutter_application_3

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

Stateless And Stateful

Stateless vs Stateful

[![Flutter](https://img.icons8.com/color/48/000000/flutter.png)](https://docs.flutter.dev/ui/interactivity)[Add interactivity to your Flutter app]

- Stateless Widget
    
    stl atau stateless adalah aplikasi yang tidak membutuhkan perubahan state atau keadaan layar. A stateless widget never changes Icon, Button, and Text are Example of stateless widget Stateless. widgets subclass [`StatelessWidget`](https://api.flutter.dev/flutter/widgets/StatelessWidget-class.html) (bahasa indo : statless widget tidak pernah berubah contoh dari widget ini yaitu Icon, Button, dan juga Text. Stateless tidak terdapat perubahan screen, ui, dan lain sebagainya.

    ![stateless.PNG](https://prod-files-secure.s3.us-west-2.amazonaws.com/abcb1cf6-3200-4445-9cf9-e3c071b63f38/b78591bc-145a-469c-9cee-4be5ad462940/stateless.png)

- Stateful Widget
    
    stf atau stateful adalah aplikasi yang membutuhkan perubahan state atau keadaan. A *stateful* widget is dynamic: for example, it can change its appearance in response to events triggered by user interactions or when it receives data. [`Checkbox`](https://api.flutter.dev/flutter/material/Checkbox-class.html), [`Radio`](https://api.flutter.dev/flutter/material/Radio-class.html), [`Slider`](https://api.flutter.dev/flutter/material/Slider-class.html), [`InkWell`](https://api.flutter.dev/flutter/material/InkWell-class.html), [`Form`](https://api.flutter.dev/flutter/widgets/Form-class.html), and [`TextField`](https://api.flutter.dev/flutter/material/TextField-class.html) are examples of stateful widgets. Stateful widgets subclass [`StatefulWidget`](https://api.flutter.dev/flutter/widgets/StatefulWidget-class.html). (bahasa indo : stateful widget adalah dapat berubah2 sebagai contoh suatu bisa berubah yaitu penampilan dalam sebuah response melalui sebuah  peristiwa yang di picu oleh interaksi pengguna atau saat menerima sebuah data. contoh Checkbox, Radio, Slider, Inkwee, Form dan TextField adalah sebuah stateful widgets.

![statefull.PNG](https://prod-files-secure.s3.us-west-2.amazonaws.com/abcb1cf6-3200-4445-9cf9-e3c071b63f38/d2e48ade-37da-4239-ae89-cef129dedd85/statefull.png)

![statefull2.PNG](https://prod-files-secure.s3.us-west-2.amazonaws.com/abcb1cf6-3200-4445-9cf9-e3c071b63f38/eb89ba05-6aed-4216-a639-d8f0a04ce57a/statefull2.png)

- State Management
    
    State Manegement adalah perubahan screen dimana seluruh screen akan di render ulang dan mengupdate seluruh screen. Widget build merender screen ulang semuanya.

![code-snapshot.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/abcb1cf6-3200-4445-9cf9-e3c071b63f38/24660f77-cf58-475c-9121-4d3857d505e5/code-snapshot.png)