<head>
    <title>Form test</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11"></script>
    <style>
      body {
        font-family: 'Roboto', sans-serif;
        font-size: 3em;
        background-color: #f4f4f9;
      }
      .container {
        max-width: 100%;
        background-color: #fff;
        padding: 2em;
        border-radius: 25px;
        box-shadow: 0 0 50px rgba(0, 0, 0, 0.5);
      }
      .form-control, .form-select {
        font-size: 1em;
        margin-bottom: 1em;
        border-radius: 30px; /* Add rounded corners to input fields */
      }
      .form-select {
        width: 100%; /* Increased width */
        padding: 0.5em;
        border: 1px solid #ced4da;
        appearance: none;
        background-color: #fff;
        background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4 5"><path fill="none" stroke="rgba(0, 0, 0, 0.25)" stroke-width="1" d="M2 0 L0 2 L4 2 Z"/></svg>');
        background-repeat: no-repeat;
        background-position: right 0.75em center;
        background-size: 8px 10px;
      }
      .btn {
        font-size: 1.5em;
        width: 100%;
        display: block;
        margin: 0 auto;
        background-color: #007bff;
        border: none;
        border-radius: 30px;
      }
      .btn:hover {
        background-color: #0056b3;
      }
      h1 {
        color: #b2ebf2;
        text-align: center; /* จัดตำแหน่งข้อความให้อยู่กลาง */
        margin-bottom: 1.3em; /* Reduced margin-bottom */
        font-size: 0.9em;
      }
      h3 {
        color: #333;
        text-align: center;
        margin-top: 0;
        margin-bottom: 0.1em; /* Reduced margin-bottom */
        font-size: 1.2em;
      }
      .swal2-custom-popup {
        width: 28em; /* ปรับขนาด popup */
        font-size: 0.35em; /* ลดขนาดตัวหนังสือใน popup */
      }
      .swal2-custom-content {
        font-size: 0.35em; /* ลดขนาดตัวหนังสือในเนื้อหาภายใน popup */
      }
    </style>
  </head>
<body>
  <div class="pt-1"></div>
  <div class="container">
    <div>
      <h3 class="text-center">แบบบันทึกการลา</h3>
    </div>
    <form method="post" autocomplete="off" name="hello-sheet">
      <div class="form-group">
        <label for="ชื่อ">ชื่อ</label>
        <div class="form-group">
          <select id="ชื่อ" name="ชื่อ" class="form-select" required>
            <option value=""></option>
            <option value="นางรภัทภร สิทธิวงศ์">นางรภัทภร สิทธิวงศ์</option>
            <option value="นางณัฐิยา ดาราย้อย">นางณัฐิยา ดาราย้อย</option>
            <option value="น.ส.กานดา เก็จรัมย์">น.ส.กานดา เก็จรัมย์</option>
            <option value="นายจิรศักดิ์ ยอดชะลูด">นายจิรศักดิ์ ยอดชะลูด</option>
            <option value="นางฐิติรัตน์ ดำรงค์">นางฐิติรัตน์ ดำรงค์</option>
            <option value="น.ส.ดวงสมร ช่วงชัย">น.ส.ดวงสมร ช่วงชัย</option>
            <option value="นายจิรวัฒน์ ดีล้อม">นายจิรวัฒน์ ดีล้อม</option>
            <option value="นายนิติศักดิ์ หนองเรือง">นายนิติศักดิ์ หนองเรือง</option>
            <option value="นายพีระพล ศรีวงสุข">นายพีระพล ศรีวงสุข</option>
            <option value="นางศรินภา เชียนรัมย์ มอบยิ่ง">นางศรินภา เชียนรัมย์ มอบยิ่ง</option>
            <option value="นายคมกริช โฉมงาม">นายคมกริช โฉมงาม</option>
            <option value="น.ส.ปริชญา สีหานู">น.ส.ปริชญา สีหานู</option>
            <option value="น.ส.กานต์ติมา ทองน้อย">น.ส.กานต์ติมา ทองน้อย</option>
            <option value="น.ส.สุภาวรรณ ดำเสนา">น.ส.สุภาวรรณ ดำเสนา</option>
            <option value="นายมาโนช เจริญยิ่ง">นายมาโนช เจริญยิ่ง</option>
            <option value="น.ส.สุนิษา สัตบุตร">น.ส.สุนิษา สัตบุตร</option>
            <option value="นางวิภารัตน์ จันทะนุภา">นางวิภารัตน์ จันทะนุภา</option>
            <option value="น.ส.ศันสนีย์ หมายดี">น.ส.ศันสนีย์ หมายดี</option>
            <option value="นายอรรณพ เการัมย์">นายอรรณพ เการัมย์</option>
            <option value="นายธีรพงษ์ บุษยงค์">นายธีรพงษ์ บุษยงค์</option>
            <option value="น.ส.กมลลักษณ์ ยอดเครือ">น.ส.กมลลักษณ์ ยอดเครือ</option>
          </select>
        </div>
      <div class="form-group">
        <label for="ประเภทการลา">ประเภทการลา</label>
        <div class="form-group">
        <select id="leaveType" name="ประเภทการลา" class="form-select" required>
              <option value=""></option>
              <option value="ลาป่วย">ลาป่วย</option>
              <option value="ลากิจ">ลากิจ</option>
              <option value="ลาคลอด">ลาคลอด</option>
              <option value="ลาบวช">ลาบวช</option>
              <option value="ลาอื่นๆ">ลาอื่นๆ</option>
        </select>
        </div>
      <div class="form-group">
        <label for="เนื่องจาก">เนื่องจาก</label>
        <input type="text" class="form-control" placeholder="" name="เนื่องจาก">
      </div>
      <div class="form-group">
        <label for="จำนวนวันลา">จำนวนวันลา</label>
        <div class="form-group">
          <select id="leaveDays" name="จำนวนวันลา" class="form-select" required>
                <option value=""></option>
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
                <option value="5">5</option>
          </select>
      </div>
      <div class="form-group">
        <label for="เริ่มวันที่">เริ่มวันที่</label>
        <input type="date" id="startDate" name="เริ่มวันที่" class="form-select" required>
      </div>  
      <div class="form-group">
        <label for="ถึงวันที่">ถึงวันที่</label>
        <input type="date" id="endDate" name="ถึงวันที่" class="form-select" required>
      </div>  
      <button type="submit" name="submit" value="Send message" class="btn btn-primary">บันทึก</button>
  </div>
 <script>
  document.addEventListener('DOMContentLoaded', () => {
    const scriptURL = 'https://script.google.com/macros/s/AKfycbw3c4H3wOmuvn3KyoXPT7BSqwob7P2pasXN7AeG1MMDcKiQr84PTODy2QPbqhzEJpjdNw/exec';
    const form = document.forms['hello-sheet'];

    form.addEventListener('submit', async (e) => {
      e.preventDefault();
      Swal.fire({
        title: 'กรุณารอสักครู่',
        text: 'ระบบกำลังประมวลผล...',
        icon: 'info',
        allowOutsideClick: false,
        customClass: {
          popup: 'swal2-custom-popup',
          content: 'swal2-custom-content'
        },
        didOpen: () => {
          Swal.showLoading();
        }
      });
      try {
        const response = await fetch(scriptURL, {
          method: 'POST',
          body: new FormData(form)
        });
        if (response.ok) {
          const formData = new FormData(form);
          let summaryContent = '<ul>';
          
          // สร้างเนื้อหาสรุปข้อมูลจากฟอร์ม
          formData.forEach((value, key) => {
            summaryContent += `<li><strong>${key}</strong>: ${value}</li>`;
          });

          summaryContent += '</ul>';
          
          // แสดงหน้าต่างสรุปข้อมูลหลังจากส่งข้อมูลสำเร็จ
          Swal.fire({
            title: 'ใบลาสำเร็จ',
            html: `<h1>แคปหน้าจอส่งในกลุ่มไลน์ทุกครั้ง</h1><p>เรียน ผู้อำนวยการโรงเรียนสูงเนินพิทยาคม ข้าพเจ้าขออนุญาตตามรายละดังแนบ</p>${summaryContent}`,
            icon: 'success',
            confirmButtonText: 'ปิด',
            customClass: {
              popup: 'swal2-custom-popup', // ใช้คลาสที่กำหนดไว้
              content: 'swal2-custom-content' // ใช้คลาสที่กำหนดไว้
            }
          }).then(() => {
            form.reset(); // Reset form fields after the alert is confirmed
          });
        } else {
          throw new Error('Network response was not ok');
        }
      } catch (error) {
        Swal.close(); // ปิดข้อความรอ
        Swal.fire({
          title: 'เกิดข้อผิดพลาด!',
          text: 'ไม่สามารถบันทึกข้อมูลได้',
          icon: 'error',
          confirmButtonText: 'ตกลง'
        });
        console.error('Error!', error.message);
      }
    });
  });
</script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
