# The empty cube
*03 October 2018*

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis fermentum mollis placerat. Sed tempus massa imperdiet pharetra mattis. Nullam condimentum urna tortor, ut iaculis mauris sodales ut. Pellentesque sed euismod purus. Donec ornare finibus erat sit amet bibendum. Vivamus neque erat, hendrerit in enim eu, euismod ullamcorper magna. Praesent id lectus in erat posuere elementum vitae sed neque. Interdum et malesuada fames ac ante ipsum primis in faucibus. Mauris nec justo congue, blandit eros non, accumsan tortor. Sed accumsan pretium gravida. Donec turpis enim, pharetra a tincidunt vitae, tempor vel urna. Pellentesque scelerisque turpis diam, vitae blandit magna mollis id. Sed semper erat vel scelerisque molestie. Nam facilisis dignissim elit id aliquam. Proin semper ultricies quam iaculis dapibus. Pellentesque vestibulum sem non nulla dapibus eleifend.

![cube](img/posts/the-empty-cube/cube.png "cube")

Donec rhoncus in diam eget porttitor. Nam sit amet metus nec dolor aliquet lobortis varius nec nulla. Sed eget arcu id quam aliquet dignissim. Nunc laoreet hendrerit nibh, eget tincidunt lorem efficitur auctor. Sed ac nunc turpis. Cras in tempor odio. Ut aliquet eleifend magna, ac volutpat metus rhoncus ut. Vestibulum lorem mauris, congue in molestie sit amet, varius sed arcu. Phasellus tempus velit et tellus mollis, nec rutrum diam aliquet.

Donec non efficitur ipsum, imperdiet scelerisque sem. Sed eu ornare leo, sit amet laoreet purus. Suspendisse sit amet vestibulum felis, non consequat turpis. Proin ipsum massa, tincidunt vitae sem non, sollicitudin efficitur erat. Nam maximus sed tortor non tincidunt. Quisque iaculis urna nibh, et accumsan erat efficitur et. Duis lobortis nisi eget justo sodales, eget tristique ante dignissim. Mauris odio magna, convallis in sagittis ac, dictum sed felis. Curabitur interdum luctus lacus, vel placerat tellus consectetur ac.

```go
for _, line := range lines {
  inserted := false
  for k, v := range m {
    if strings.Contains(line, k) {
      lineReplaced := strings.Replace(line, k, v, -1)
      resultL = append(resultL, lineReplaced)
      inserted = true
    }
  }
  if inserted == false {
    resultL = append(resultL, line)
  }
}
```
Aenean lacinia nulla ut congue porttitor. Etiam vitae eleifend massa. In arcu turpis, dignissim vitae viverra nec, imperdiet at libero. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Proin laoreet libero libero, quis viverra ante imperdiet vel. Sed quis arcu ac elit sollicitudin consectetur nec eget velit. Aliquam dictum vel orci ut bibendum. Cras nunc massa, efficitur id quam non, tempus mollis mauris. Aliquam viverra imperdiet ex id scelerisque. Pellentesque pellentesque convallis ipsum. Maecenas consequat tempor augue non porta. Mauris facilisis neque pretium, lacinia elit eu, blandit augue. Proin porta sem dolor, in auctor lectus facilisis sit amet. Donec porttitor accumsan leo et fringilla.

Aliquam blandit massa neque, in pellentesque sem lacinia quis. Etiam faucibus consequat urna nec efficitur. Aenean rutrum vestibulum efficitur. Curabitur vel molestie justo. Ut cursus felis eget turpis luctus dictum. Nullam elementum mi facilisis nunc maximus, auctor gravida libero pretium. Duis dui justo, fringilla sollicitudin est vehicula, sollicitudin mattis mauris.
