# Use Case Diagram
## Çalışma Modellerinin Analizi Sistemi

mermaid
flowchart LR
    A([Araştırmacı])

    subgraph S["Çalışma Modellerinin Analizi Sistemi"]
        U1([Veri setini yükleme])
        U2([Çalışan performansını analiz etme])
        U3([İş-özel hayat dengesini analiz etme])
        U4([İşten ayrılma eğilimini analiz etme])
        U5([Çalışma modellerini karşılaştırma])
        U6([Grafik ve rapor oluşturma])

        U1 --> U2
        U1 --> U3
        U1 --> U4
        U2 --> U5
        U3 --> U5
        U4 --> U5
        U5 --> U6
    end

    A --- U1
    A --- U2
    A --- U3
    A --- U4
    A --- U5
    A --- U6


## Açıklama

Bu diyagram, araştırmacının veri setini yüklemesini, çalışan performansı, iş-özel hayat dengesi ve işten ayrılma eğilimini analiz etmesini ve çalışma modellerini karşılaştırarak sonuçları raporlamasını göstermektedir.
