<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My CV - Interactive Computer Graphics</title>
<style>
  * { box-sizing: border-box; }
  body {
    font-family: 'Segoe UI', Tahoma, sans-serif;
    background: #f4f4f4;
    margin: 0;
    padding: 0;
    color: #222;
  }
  .container {
    max-width: 800px;
    margin: 40px auto;
    background: #fff;
    padding: 40px;
    border-radius: 10px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  }
  header {
    text-align: center;
    border-bottom: 3px solid #2c3e50;
    padding-bottom: 20px;
    margin-bottom: 30px;
  }
  header h1 {
    margin: 0;
    font-size: 32px;
    color: #2c3e50;
  }
  header p {
    margin: 5px 0 0;
    color: #666;
  }
  .topic-badge {
    display: inline-block;
    background: #2c3e50;
    color: #fff;
    padding: 6px 16px;
    border-radius: 20px;
    font-size: 14px;
    margin-top: 10px;
  }
  section {
    margin-bottom: 25px;
  }
  section h2 {
    color: #2c3e50;
    border-left: 5px solid #2c3e50;
    padding-left: 10px;
    font-size: 20px;
  }
  ul {
    padding-left: 20px;
  }
  li {
    margin-bottom: 6px;
  }
  .contact a {
    color: #2c3e50;
    text-decoration: none;
  }
  .demo-link {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 20px;
    background: #2c3e50;
    color: #fff;
    border-radius: 6px;
    text-decoration: none;
  }
  .demo-link:hover {
    background: #1a252f;
  }
  .portfolio-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
    gap: 16px;
  }
  .work-card {
    display: block;
    min-height: 165px;
    padding: 20px;
    border: 1px solid #dbe2e8;
    border-radius: 10px;
    background: linear-gradient(135deg, #ffffff, #edf4f8);
    color: #222;
    text-decoration: none;
    box-shadow: 0 2px 7px rgba(0, 0, 0, 0.06);
    transition: transform 0.18s ease, box-shadow 0.18s ease;
  }
  .work-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 8px 18px rgba(44, 62, 80, 0.18);
  }
  .work-card h3 {
    margin: 0 0 10px;
    color: #2c3e50;
  }
  .work-card p {
    margin: 0;
    color: #566573;
    line-height: 1.5;
  }
  .open-work {
    display: inline-block;
    margin-top: 16px;
    color: #2c3e50;
    font-weight: 700;
  }
</style>
</head>
<body>

<div class="container">

  <header>
    <h1>พงษ์กร นรสิงห์</h1>
    <p>นักศึกษา / สาขา วิทยาการคอมพิวเตอร์ มหาวิทยาลัยเกษตรศาสตร์ วิทยาเขตกำแพงแสน</p>
    <span class="topic-badge">Interactive Computer Graphics</span>
  </header>

  <section class="contact">
    <h2>ติดต่อ</h2>
    <p>Email: <a href="mailto:youremail@example.com">Phongsakon.n@ku.th</a></p>
    <p>GitHub: <a href="https://github.com/phongsakonn-nut" target="_blank">github.com/phongsakonn-nut</a></p>
  </section>

  <section>
    <h2>การศึกษา</h2>
    <ul>
      <li>กำลังศึกษาปริญญาตรี สาขาวิทยาการคอมพิวเตอร์ มหาวิทยาลัยเกษตรศาสตร์ วิทยาเขตกำแพงแสน  (ปี 2567 - 2569)</li>
      <li>มัธยมศึกษาตอนปลาย โรงเรียน บรรหารแจ่มใส่วิทยา 6 </li>
    </ul>
  </section>

  <section>
    <h2>ทักษะ</h2>
    <ul>
      <li>HTML / C / Java </li>
      <li>Computer Graphics (Transformation, Canvas API)</li>
      <li>ทำเบเกอร์ เล่นฟุตบอล</li>
    </ul>
  </section>

  <section>
    <h2>ผลงาน Interactive Computer Graphics</h2>
    <div class="portfolio-grid">
      <a class="work-card" href="https://phongsakonn-nut.github.io/13/700_transfromation.html" target="_blank" rel="noopener">
        <h3>Transformation</h3>
        <p>สาธิตการแปลงรูปทรงสองมิติด้วย Transformation</p>
        <span class="open-work">เปิดผลงาน →</span>
      </a>

      <a class="work-card" href="https://phongsakonn-nut.github.io/13/paint.html" target="_blank" rel="noopener">
        <h3>Assignment #2: Paint</h3>
        <p>เว็บวาดภาพแบบโต้ตอบด้วย Canvas API</p>
        <span class="open-work">เปิดผลงาน →</span>
      </a>

      <a class="work-card" href="https://phongsakonn-nut.github.io/13/doghome.html" target="_blank" rel="noopener">
        <h3>Assignment #3: Dog Home</h3>
        <p>ฉากสามมิติ WebGL พร้อม PBR และเมนูปรับตำแหน่งกับความสว่างของแสง</p>
        <span class="open-work">เปิดผลงาน →</span>
      </a>
    </div>
  </section>


</div>

</body>
</html>
