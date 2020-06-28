<h1 align="center">Hava Kalite Takip Uygulaması</h1>


> Uygulama, kullanıcınun bulundupu konumdaki havanın kalitesini takip etmesini, hava kirliliğine neden olan durumları uygulama üzerinden yetkililere bildirmesini amaçlamaktadır. Uygulamaya aile üyeleri eklenebilmekte ve bu üyelerin bulundukları şehirlerdeki hava kalitesi takip edilebilmektedir.

## Kurulum gRPC Server Side

From the `hava_kalite_takip/AirQualityApi/air-quality-api/grpcServer/proto/Server/` directory:

 1. Run the npm install:

    ```sh
    $ npm install
    ```
 2. Run the npm install for gRPC package:

    ```sh
    $ npm i grpc    

    $ npm i @grpc/proto-loader
    ```

 2. From another terminal, run the client:

    ```sh
    $ node server.js
    ```
## Kurulum NodeJs Server Side

From the `hava_kalite_takip/AirQualityApi/air-quality-api/` directory:

 1. Run the npm install:

    ```sh
    $ npm install
    ```
 2. From another terminal, run the client:

    ```sh
    $ node server.js
    ```

## Ekran Görüntüleri

> Hava kalite takip ekranları

![a](https://user-images.githubusercontent.com/48556212/85957313-0007d380-b995-11ea-97da-95ca32ca4e38.png)

> Rapor/şikayet ekranları

![c](https://user-images.githubusercontent.com/48556212/85957316-039b5a80-b995-11ea-9667-7da1cff74725.png)

> Aile üyesi ekleme ve hava takip ekranları

![b](https://user-images.githubusercontent.com/48556212/85957315-026a2d80-b995-11ea-9c7a-ecc74c617d93.jpg)


## Kullanılan Teknolojiler

* Google Maps Api
* Air Quality Index Api
* Android Studio 3.6
* Java 1.8
* Node.js 
* MongoDB 
* Firebase Cloud Storage
* gRPC
