# Almofire-Codable
Integrated API function (Almofire with Codable)

API function
```
    let parameters: [String: Any] = ["key": "value"]
    WebServiceManager.shared.callWebService(url, parameters: parameters, method: .post) { (response: [T]?, error, errorMessage)  in
      print(response?.count ?? 0)
    }
```
