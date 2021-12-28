# ASP.NET Core WebApi Sample with HATEOAS, Versioning & Swagger

Bu depoda, ASP.NET Core ile bir WebAPI'nin nasıl oluşturulacağına dair basit bir başlangıç noktası vermek istiyorum.

Bu depo, FoodItems ile ilgilenen bir denetleyici içerir. GET/POST/PUT/PATCH/DELETE yapabilirsiniz.

Bu yardımcı olur umarım.

Buradaki örneklere bakın:

## Versions
> *http://localhost:29435/swagger*

![](https://raw.githubusercontent.com/FabianGosebrink/ASPNETCore-WebAPI-Sample/main/.github/versions.jpg)

## GET all Foods
> *http://localhost:29435/api/v1/foods*

![](https://raw.githubusercontent.com/FabianGosebrink/ASPNETCore-WebAPI-Sample/main/.github/get.jpg)

## GET single food
> *http://localhost:29435/api/v1/foods/2*

![](https://raw.githubusercontent.com/FabianGosebrink/ASPNETCore-WebAPI-Sample/main/.github/getSingle.jpg)

## POST a foodItem
> *http://localhost:29435/api/v1/foods*
```
 {
      "name": "Lasagne",
      "type": "Main",
      "calories": 3000,
      "created": "2017-09-16T17:50:08.1510899+02:00"
  }
```
![](https://raw.githubusercontent.com/FabianGosebrink/ASPNETCore-WebAPI-Sample/main/.github/post.jpg)

## PUT a foodItem
> *http://localhost:29435/api/v1/foods/5*
```
{
    "name": "Lasagne2",
    "type": "Main",
    "calories": 3000,
    "created": "2017-09-16T17:50:08.1510899+02:00"
}
```
![](https://raw.githubusercontent.com/FabianGosebrink/ASPNETCore-WebAPI-Sample/main/.github/put.jpg)

## DELETE a foodItem
> *http://localhost:29435/api/v1/foods/5*

![](https://raw.githubusercontent.com/FabianGosebrink/ASPNETCore-WebAPI-Sample/main/.github/delete.jpg)