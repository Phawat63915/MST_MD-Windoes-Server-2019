# Install

## 1.Downlaod

{% embed url="https://www.microsoft.com/en-us/sql-server/sql-server-downloads" %}

## 2.Install

2.1 กดเปิดตัวติดตั้ง และ เลือกติดตั้งแบบ Custom

<div>

<figure><img src="../../../../.gitbook/assets/Screenshot (6).png" alt=""><figcaption></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (8).png" alt=""><figcaption><p>กดหัวข้อ Custom</p></figcaption></figure>

</div>

2.2 กดปุ่ม Install เพื่อทำหารติดตั้ง

(!) หากต้องการเปลี่ยนที่อยู่ติดตั้งโปรแกรมสามารถ กดปรับเปลี่ยนได้ตรง Browse

<div>

<figure><img src="../../../../.gitbook/assets/Screenshot (10).png" alt=""><figcaption><p>กดปุ่ม Install</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (14).png" alt=""><figcaption></figcaption></figure>

</div>

2.3 เลือกหัวต้อง Installation และ เลือก New Sql Server standalone Installation or add features to an eisting installation เพื่อทำการติดตั้ง Sql Serer

<div>

<figure><img src="../../../../.gitbook/assets/Screenshot (20).png" alt=""><figcaption><p>เลือกหัวข้อ Installation</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (21).png" alt=""><figcaption><p> กดเลือก New Sql Server standalone Installation or add features to an eisting installation เพื่อทำการติดตั้ง</p></figcaption></figure>

</div>

## 3.Config

3.1 เลือก Specify a free edtion เป็น Developer

(!) Developer แนะนำให้เลือกเป็นอันนี้ ในกรณีที่ใช้ในการทดสอบเท่าเท่านั้น ไม่แนะนำให้นำไปใช้ตอนขึ้น Product

<div>

<figure><img src="../../../../.gitbook/assets/Screenshot (23).png" alt=""><figcaption><p>เลือก Specify a free edtion เป็น Developer</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (24).png" alt=""><figcaption><p>กดปุ่ม Next</p></figcaption></figure>

</div>

3.2 ติด CheckBox I accept the license terms and Privacy Statment และ กดปุ่ม Next

<div>

<figure><img src="../../../../.gitbook/assets/Screenshot (25).png" alt=""><figcaption><p>ติด CheckBox I accept the license terms and Privacy Statment</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (26).png" alt=""><figcaption><p>กดปุ่ม Next</p></figcaption></figure>

</div>

3.3 กดปุ่ม Next และ กดปุ่ม Next

<div>

<figure><img src="../../../../.gitbook/assets/Screenshot (28).png" alt=""><figcaption><p>กดปุ่ม Next</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (30).png" alt=""><figcaption><p>กดปุ่ม Next</p></figcaption></figure>

</div>

3.4 เอากดติด CheckBox Azure Extension for SQL Server ออก และ กดปุ่ม Next

<div>

<figure><img src="../../../../.gitbook/assets/Screenshot (31).png" alt=""><figcaption><p>ติด CheckBox Azure Extension for SQL Server ออก</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (32).png" alt=""><figcaption><p>กดปุ่ม Next</p></figcaption></figure>

</div>

3.5 ติด CheckBox หัวข้อ Instance Features ที่ Database Engine Services และ ติด CheckBox ที่ Full-Text and Semantic Extractions for Search จากนั้น กดปุ่ม Next

(!) ปกติหลักๆ ถ้าไม่ได่ทำอะไรมากจะใช้แค่สองตัวเลือกที่ติด CheckBox นี้ไป

<div>

<figure><img src="../../../../.gitbook/assets/Screenshot (37).png" alt=""><figcaption><p>ติก CheckBox Database Engine</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (38).png" alt=""><figcaption><p>ติด CheckBox Full-Text and Semantic Extractions for Search</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (39).png" alt=""><figcaption><p>กดปุ่ม Next</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (40).png" alt=""><figcaption></figcaption></figure>

</div>

3.6 กดปุ่ม Next และกดปุ่ม Next

(!) หากต้องการเปลี่ยนชื่อ Instance สามารถเปลี่ยน radio button ไปเป็น  Named Instance ได้และเปลี่ยน ชื่อตรง Input และ เปลี่ยน Instance ID ตรง Input ที่ 2&#x20;

<div>

<figure><img src="../../../../.gitbook/assets/Screenshot (44).png" alt=""><figcaption><p>กดปุ่ม Next</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (47).png" alt=""><figcaption></figcaption></figure>

</div>

3.7 เลือก Radio Button ที่ Mix Mode (SQL Server authentiction and Windoes authentiction) และใส่รหัสผ่าน และ กดปุ่ม Add Current User และกดปุ่ม Next

(!) สำหรับเพิ่ม Add Current User หากเป็นการทดสอบหรือไม่ได้ ขึ้น Product เราเพิ่มแค่ User เดียวก็เพียงพอแล้ว ส่วน Mix Mode (SQL Server authentiction and Windoes authentiction) หากต้องการลง Database ที่  Server เราควร ตั้ง User ผู้ใช้แบบไม่ใช้อันบนเพราะว่า จะทำให้สามารถ login ผ่าน User SA ได้ง่ายกว่า

<div>

<figure><img src="../../../../.gitbook/assets/Screenshot (49).png" alt=""><figcaption><p>กดติด Radio Button Mix Mode (SQL Server authentiction and Windoes authentiction)</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (50).png" alt=""><figcaption><p>ใส่รหัสสผ่าน</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (51).png" alt=""><figcaption><p>ใส่รหัสผ่าน</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (52).png" alt=""><figcaption><p>กดปุ่ม Next</p></figcaption></figure>

</div>

3.8 กดปุ่ม Install

(!) หากไม่ต้องการติดตั้งใดๆ แล้วสามารถปิดได้เลย

<div>

<figure><img src="../../../../.gitbook/assets/Screenshot (53).png" alt=""><figcaption><p>กดปุ่ม Install</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (55).png" alt=""><figcaption></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (57).png" alt=""><figcaption><p>กดปุ่ม Close</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/Screenshot (60).png" alt=""><figcaption><p>กดปุ่ม ปิด </p></figcaption></figure>

</div>
