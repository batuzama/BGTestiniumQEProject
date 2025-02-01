# Testinium QE Test Otomasyon Projesi

Bu proje, **Selenium** ve **Gauge (BDD)** kullanılarak geliştirilmiş bir test otomasyon projesidir. **Java** programlama diliyle yazılmış olup, **Maven** proje yapısı kullanılmıştır. 
Testinium QE projesi için yapılmıştır.

## Proje Hakkında

Bu proje, web tabanlı uygulamalar için otomatik test senaryoları oluşturmayı ve çalıştırmayı amaçlamaktadır. 

### Proje Özellikleri:
- **Selenium WebDriver** kullanılarak web tarayıcıları üzerinde test otomasyonu yapılır.
- **Gauge BDD** frameworkü kullanılarak test senaryoları yazılır.
- **Maven** ile bağımlılıklar yönetilir ve proje yapılandırılır.
- Gauge Report kullanılarak test raporları oluşturulur. Raporlar report klasöründen erişilebilir.

---

## Dependency'ler

Projede kullanılan Dependency'ler örnekte aşşağıda verilmiştir.

```xml
<dependencies>
   <dependency>
      <groupId>com.thoughtworks.gauge</groupId>
      <artifactId>gauge-java</artifactId>
      <version>0.9.1</version>
      <scope>test</scope>
   </dependency>

   <dependency>
      <groupId>org.seleniumhq.selenium</groupId>
      <artifactId>selenium-java</artifactId>
      <version>3.141.59</version>
      <scope>test</scope>
   </dependency>

   <dependency>
      <groupId>org.junit.jupiter</groupId>
      <artifactId>junit-jupiter-api</artifactId>
      <version>${junit5.version}</version>
   </dependency>

   <dependency>
      <groupId>org.apache.logging.log4j</groupId>
      <artifactId>log4j-api</artifactId>
      <version>${log4j.version}</version>
   </dependency>

   <dependency>
      <groupId>org.apache.logging.log4j</groupId>
      <artifactId>log4j-core</artifactId>
      <version>${log4j.version}</version>
   </dependency>

</dependencies>
```

Dependency'leri eklemek için Maven projenizin `pom.xml` dosyasına yukarıdaki kodu ekleyin.

---

## Tag Yapılandırması

Gauge kullanarak farklı test senaryolarını gruplamak ve yönetmek için etiketleme (tagging) yapısı kullanılabilir. 

Senaryo Başlığı
---------------
tags: Login, Hesabim, HesabiDuzenle, ParaEkle, ParaGonder
```
---

## Kurulum

Projeyi çalıştırmak için aşağıdaki adımları izleyin:

### Gereksinimler

1. **Java** (minimum JDK 1.8)
2. **Maven**
3. **Gauge**
4. **IDE**
   
### Çalıştırma Adımları

1. Bu repoyu klonlayın:
   ```bash
   git clone https://github.com/kullanici_adiniz/proje_adi.git
   ```

2. Proje dizinine gidin:
   ```bash
   cd proje_adi
   ```

3. Maven bağımlılıklarını yükleyin:
   ```bash
   mvn clean install
   ```

4. Testleri çalıştırın:
   ```bash
   gauge run specs
   ```

---

## Versiyon Bilgileri

| Araç                | Versiyon |
|---------------------|----------|
| Selenium WebDriver  | 3.141.59 |
| Gauge Framework     | 0.9.1    |
| Java                | 1.8      |
| Maven               | 1.8      |
| Junit5              | 5.8.2    |
| Log4j               | 2.17.2   |


