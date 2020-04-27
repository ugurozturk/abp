# Otomatil API Controller ları

Bir defa [uygulama servisi](../Application-Services.md) oluşturduğunuz zaman, genellikle API Controller ı oluşturup bu servisi HTTP (REST) API uç noktası olarak görmek istersiniz. Bir tipik API Controller 'ı uygulama servislerini çağırma ve REST API attribute leri [HttpGet], [HttpPost], [Route] dışında bir şey yapmaz.

ABP **otomatik olarak** sizin uygulama servislerinizi API Controllerları gibi toplar. Genellikle detaylı konfigirasyonlarını dikkat etmenize gerek olmaz fakat tam anlamıyla kişiselleştirebilirsiniz.

## Konfigürasyon
