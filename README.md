![crayon_logo](https://github.com/wuuuugi/shopping/assets/137017155/fff55294-d8ef-4f0b-805d-0bbda4a85ba3)
<div style="text-align: center;"><h1>CRAYON</h1></div>

# 목차
1. [프로젝트 소개](#프로젝트-소개)
2. [서비스 내용](#서비스-내용)
3. [개발 기간](#개발-기간)
4. [기술 스택](#기술-스택)
5. [주요 기능](#주요-기능)
6. [팀 소개](#팀-소개)
7. [프로젝트 구성도](#프로젝트-구성도)
8. [시연 화면](#시연-화면)
<br>
<br>

# 📖프로젝트 소개

> 'Crayon'을 소개합니다 ( •⌄• ू )✧( •⌄• ू )✧( •⌄• ू )✧
> 
한정판 의류 및 신발등 다양한 한정판 제화를 좋아하는 사람들을 위한 한정판 상품 판매/구매 및 정보 제공이 가능한 웹 플랫폼 서비스입니다.
<br>
<br>

## 📜서비스 내용

- 판매자와 구매자의 경계없이 모든 회원이 판매자와 구매자가 될 수 있습나디. 판매자는 상품등록이 가능하고 구매자는 상품구매가 가능합니다. 또, 판매자도 상품구매가 가능하고, 구매자도 상품등록이 가능합니다.
- 사용자가 지정한 검색 조건으로 상품을 검색 할 수 있습니다. 그리고 카테고리별, 인기순으로도 상품 조회가 가능합니다.
- 한정판 상품의 시세 정보를 제공합니다.
- 한정판 상품의 경매 등록 및 낙찰 서비스를 제공합니다.
<br>
<br>

## 📆개발 기간 
<b>2023-08-09 ~ 2023.08.29</b>
<br>
<br>


## 🛠기술 스택

<div><img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"></div>
<div><img src="https://img.shields.io/badge/HTML-0175C2?style=for-the-badge&logo=dart&logoColor=white"> <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=CSS3&logoColor=white">  <img src="https://img.shields.io/badge/Java Script-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"></div>
<div><img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=Vue.js&logoColor=white">  <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jQuery&logoColor=white"></div>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
<br>
<br>

## 💻주요 기능
- 메인페이지 이미지 슬라이더
  ```
  메인페이지에서 이미지 뿐만 아니라 .gif형식의 파일도 슬라이드를 통해 사용자에 노출됩니다.
  ```
- 경매 물품 등록
  ```
  사용자가 원하는 시기에 경매를 등록하여 중고 물품 경매를 진행하는 기능을 제공하고, 누군가 입찰했을시 입찰가와 입찰자 정보는 제공되지 않고, 입찰날짜만 제공됩니다.
  시간이 만료되었을 때 가장 높은 금액을 제시한 사용자가 중고 물품을 낙찰 받는 시스템입니다.
  ```
- 사용자가 지정한 조건으로 상품 검색
  ```
  사용자가 원하는 조건으로 필터링하여 상품을 검색할 수 있습니다.
  ```
- 상품 구매 및 판매 그리고 등록
  ```
  여러 사용자들이 등록한 상품을 구매하고 판매 할 수 있습니다.
  상품 등록 시 구매 및 판매를 선택 할 수 있고, 결제는 플랫폼내의 포인트로 가능합니다.
  ```
- 주소, 결제, 차트 API
  ```
  사용자 마이 페이지에서 배송받을 주소를 주소 API를 통해 등록할 수 있습니다.
  쇼핑몰내에서 결제시 사용되는 포인트를 충전 할 때 결제 API를 통해 충전 할 수 있습니다.
  상품 상세 페이지에서 차트 API를 활용해서 사용자들에게 최근 거래기준으로 최근 거래가를 그래프로 제공합니다.
  ```
- 상품을 카테고리, 인기순 별 조회하기
  ```
  여러 사용자가 등록한 상품을 카테고리 별로 조회가 가능하며 인기순등 다양한 조건으로 상품을 검색하는 기능을 제공합니다.
  ```
## 👪팀 소개
<table>
  <tr>
    <th>강도현(FE)</th>
    <th>장승호(FE)</th>
    <th>손명욱(BE)</th>
    <th>서보규(BE)</th>
    <th>이찬신(BE)</th>
  </tr>
  <tr>
    <th>
      <div>로그인,아이디 비밀번호찾기</div>
      <div>회원가입, 고객센터, 상품페이지</div>
      <div>포인트 충전,경매페이지</div>
    </th>
    <th>
      <div>웹디자인,화면설계이미지</div>
      <div>제작 데이터 수집 CSS전제 정비</div>
      <div>메인 페이지 슬라이더</div>
      <div>로고 에니메이션</div>
    </th>
    <th>
      <div>💡팀장💡</div>
      <div>경매 페이지</div>
      <div>고객센터</div>
      <div>DB설계 데이터 수집</div>
    </th>
    <th>
      <div>회원가입</div>
      <div>스타일 게시판</div>
      <div>상품 이미지 출력</div>
      <div>상품 등록</div>
      <div>상품 판매</div>
    </th>
    <th>
      <div>구매, 판매 내역</div>
      <div>마이페이지</div>
      <div>로그인 정보</div>
      <div>프로필관리 주소록</div>
      <div>결제 내역</div>
      <div>포안트 충전</div>
    </th>
  </tr>
</table>

## 🚀 내 역할
### 회원가입
1. 아이디 중복 방지를 예방하기 위해 중복체크 서비스도 제공합니다.
```
fnCheck : function(){
			var self = this;
			var nparmap = {uId : self.user.userId};
			console.log(self.user.userId);
			$.ajax({
                url : "/user/selectId.dox",
                dataType:"json",	
                type : "POST", 
                data : nparmap,
                success : function(data) { 
                	console.log(data.info);
                	if(data.info != undefined){
                		alert("중복된 아이디가 있습니다");
                	} else {
                		alert("사용 가능한 아이디입니다.");
                		self.joinFlg = true;
                	}  
                }
            });
```
2. 정규식을 활용하여 조건을 만족할 때에만 회원가입이 원할하게 진행 될 수 있게 서비스를 제공합니다.
```
fnPwdCheck : function() {
			var self = this;
			/* var userPwd = self.user.userPwd1; */
			var regex = /^[a-zA-Z0-9]{8,16}$/; // 비밀번호 정규식
			if(!regex.test(self.user.userPwd1)){
				self.message = "비밀번호는 영문 대소문자와 숫자 포함 8자리 이상이어야 합니다.";
			}else {
				self.message = "";
			}
```
### 스타일 게시판 (사진 업로드 위주의 sns형 커뮤니티기반의 리뷰게시판)
1. 게시글 내용 및 태그상품정보 업로드가 가능합니다.
```
	@RequestMapping(value = "/addStyle.dox", method = RequestMethod.POST, produces = "application/json;charset=UTF-8")
	@ResponseBody
	public String addProduct(Model model, @RequestParam HashMap<String, Object> map) throws Exception {
		HashMap<String, Object> resultMap = new HashMap<String, Object>();
		resultMap = styleService.addStyle(map);
		return new Gson().toJson(resultMap);
	}
```
2. 스타일 사진 업로드가 가능합니다.
```
	@RequestMapping(value = "/addStyleImg.dox")
	public String styleupload(@RequestParam("file1") MultipartFile multi, @RequestParam("idx") int idx, HttpServletRequest request, HttpServletResponse response, Model model) {
		String url = null;
		String path = "c:\\img";
		try {
			String uploadpath = path;
			String originFilename = multi.getOriginalFilename();
			String extName = originFilename.substring(originFilename.lastIndexOf("."), originFilename.length());
			long size = multi.getSize();
			String saveFileName = genSaveFileName(extName);

			String path2 = System.getProperty("user.dir");
			if (!multi.isEmpty()) {
				File file = new File(path2 + "\\src\\main\\webapp\\img\\style", saveFileName);
			    multi.transferTo(file);

			    HashMap<String, Object> map = new HashMap<String, Object>();	
			    map.put("sImgName", saveFileName);
			    map.put("sImgPath", "..\\img\\style\\" + saveFileName); // Set the correct image path
			    map.put("idx", idx);

			    // Insert query execution
			    styleService.addStyleImg(map);

			    model.addAttribute("sImgName", multi.getOriginalFilename());
			    model.addAttribute("uploadPath", file.getAbsolutePath());

			    return "redirect:mypage.do";
			}
		} catch (Exception e) {
			System.out.println(e);
		}
		return "redirect:mypage.do";
	}
		// 현재 시간을 기준으로 파일 이름 생성 -> 파일 이름 중복 방지
	    private String genSaveFileName(String extName) {
	        String sImgName = "";
	        
	        Calendar calendar = Calendar.getInstance();
	        sImgName += calendar.get(Calendar.YEAR);
	        sImgName += calendar.get(Calendar.MONTH);
	        sImgName += calendar.get(Calendar.DATE);
	        sImgName += calendar.get(Calendar.HOUR);
	        sImgName += calendar.get(Calendar.MINUTE);
	        sImgName += calendar.get(Calendar.SECOND);
	        sImgName += calendar.get(Calendar.MILLISECOND);
	        sImgName += extName;
	        
	        return sImgName;
	    }
```
### 이미지를 데이터베이스에 업로드하고 출력하는 기능 구현
1. 상품 이미지 출력이 가능합니다.
```
 	@RequestMapping(value = "/productImg.dox", method = RequestMethod.POST, produces = "application/json;charset=UTF-8")
 	@ResponseBody
 	public String productImg(Model model, @RequestParam HashMap<String, Object> map) throws Exception {
 		HashMap<String, Object> resultMap = new HashMap<String, Object>();
 		Product img =productService.viewProductImg(map);
 		resultMap.put("img",img);
 		return new Gson().toJson(resultMap);
 	}
```
2. 상품이미지 업로드가 가능합니다.
```
	@RequestMapping(value = "/fileUpload.dox")
	public String result(@RequestParam("file1") MultipartFile multi, @RequestParam("productName") String productName, HttpServletRequest request, HttpServletResponse response, Model model) {
	    String url = null;
	    String path = "c:\\img";
	    try {
	        String uploadpath = path;
	        String originFilename = multi.getOriginalFilename();
	        String extName = originFilename.substring(originFilename.lastIndexOf("."), originFilename.length());
	        long size = multi.getSize();
	        String saveFileName = genSaveFileName(extName);

	        String path2 = System.getProperty("user.dir");
	        if (!multi.isEmpty()) {
	        	File file = new File(path2 + "\\src\\main\\webapp\\img\\product", saveFileName);
	            multi.transferTo(file);

	            HashMap<String, Object> map = new HashMap<String, Object>();	
	            map.put("pImgName", saveFileName);
	            map.put("pImgPath", "..\\img\\product\\" + saveFileName); // Set the correct image path
	            map.put("pName", productName);

	            // Insert query execution
	            productService.addProductImg(map);

	            model.addAttribute("pImgName", multi.getOriginalFilename());
	            model.addAttribute("uploadPath", file.getAbsolutePath());

	            return "redirect:mypage.do";
	        }
	    } catch (Exception e) {
	        System.out.println(e);
	    }
	    return "redirect:mypage.do";
	}
// 상품 이미지 보여주기
 	@RequestMapping(value = "/productImg.dox", method = RequestMethod.POST, produces = "application/json;charset=UTF-8")
 	@ResponseBody
 	public String productImg(Model model, @RequestParam HashMap<String, Object> map) throws Exception {
 		HashMap<String, Object> resultMap = new HashMap<String, Object>();
 		Product img =productService.viewProductImg(map);
 		resultMap.put("img",img);
 		return new Gson().toJson(resultMap);
 	}
// 파일 업로드 이미지 DB입력 이전 브라우저 출력을 위한 스크립트 함수
  const inputFile = document.getElementById('file1');
  const uploadedImage = document.getElementById('uploaded-image');
  
  
  inputFile.addEventListener('change', function () {
  const fileReader = new FileReader();
  fileReader.onloadend = function () {
  	uploadedImage.src = fileReader.result;
  };
  if (this.files[0]) {
  	fileReader.readAsDataURL(this.files[0]);
  }
  });
```
### 상품및 상품정보를 데이터베이스에 등록하는 기능 구현
1. 상품 관련 정보를 데이터베이스 등록할 수 있습니다.
```
	@RequestMapping(value = "/addProduct.dox", method = RequestMethod.POST, produces = "application/json;charset=UTF-8")
	@ResponseBody
	public String addProduct(Model model, @RequestParam HashMap<String, Object> map) throws Exception {
		HashMap<String, Object> resultMap = new HashMap<String, Object>();
		resultMap = productService.addProduct(map);
		return new Gson().toJson(resultMap);
	}
```
### 상품 판매 프로세스 구현
1. 상품의 판매 등록 시 기존 데이터베이스에서 해당 상품관련 정보를 불러오고 사용자 조건에 맞게 판매를 등록 할 수 있습니다.
```
//상품 정보 불러오기
			fnProList : function(){
	    		var self = this; 
	            var nparmap = {modelNum : self.modelNum};
	             $.ajax({
	                 url : "/productBuyList.dox",
	                 dataType:"json",	
	                 type : "POST", 
	                 data : nparmap,
	                 success : function(data) { 
	                 	self.proList = data.buyList;
	                 	self.proInfo = data.buyList[0];
	                 	if(data.buyList != "" &&  data.buyList != null){
	                 		self.buyFlg = true;
	                 	}else{
	                 		self.buyFlg = false;
	                 		
	                 		alert("즉시 판매 상품이 없습니다. \n판매입찰 페이지로 이동합니다.");
	                 		location.href = "/productRegister.do";
	                 	}
	                 	console.log(self.proList);
	                 	console.log(self.proInfo);
	                 	
	                 }
	             }); 
	    	},
	     	// 사이즈 조회
			fnGetSize : function () {
				var self = this;
				var nparmap = {};
				$.ajax({
					url : "size.dox",
					dataType : "json",
					type : "POST",
					data : nparmap,
					success : function(data){
						self.sList = data.size;
						console.log(data);
					}
				})
			},
			// 사이즈 버튼 클릭
			selectSize : function(proNum) {
				var self = this;
				self.selectedSize = proNum;
	       		console.log(self.selectedSize);
	   		},
```
## ✏️ 트러블 슈팅
### 상품 정보 등록시 카테고리 이슈
카테고리1 ,카테고리2 이와 같이 1번 옵션에서 값을 고르면 유기적으로 연관된 2번옵션의 값이 출력되어져야 하는데 작업 진행시 점검해보니까 1번 카테고리 값과 무관하게 2번 카테고리값이 출력되고 있었습니다.

### 회원가입 아이디, 비밀번호 무결성 관리


## 📂프로젝트 구성도
> ERD
> 
![drawio jpg](https://github.com/wuuuugi/shopping/assets/137017155/2eb4e19a-075a-4170-a5c7-095fef310907)

## 👁‍🗨시연 화면
> 메인 및 검색
> 
![메인](https://github.com/wuuuugi/shopping/assets/137017155/9f8aea7e-3ad8-4d59-bc6d-a58a6efc0680)
![메인_랭킹](https://github.com/wuuuugi/shopping/assets/137017155/b0aec8e4-dba8-4e75-8179-7b6637a863a7)
![검색창](https://github.com/wuuuugi/shopping/assets/137017155/6aee5501-efa4-41cb-9f1a-a3d9a8a39e28)
![검색결과](https://github.com/wuuuugi/shopping/assets/137017155/fd689e38-03f4-4ee0-a395-a09556ecd1b3)
---
> 경매
> 
![경매리스트](https://github.com/wuuuugi/shopping/assets/137017155/927f7c33-96ae-47b2-86c8-5b2c8a70c94d)
![경매상품등록_3](https://github.com/wuuuugi/shopping/assets/137017155/bbd210c0-f180-4006-b9be-b2d1940b2c2e)
![경매상품상세정보](https://github.com/wuuuugi/shopping/assets/137017155/68764c39-28fd-45af-b8f7-139bfdb2eb87)
---
> 상품
>
![상품등록](https://github.com/wuuuugi/shopping/assets/137017155/ead6ad49-a10a-44be-a99b-11687a4551e8)
![상품상세정보](https://github.com/wuuuugi/shopping/assets/137017155/4d212d61-69a0-4ec6-b6f5-ec898717e49b)
![판매 배송 및 결제](https://github.com/wuuuugi/shopping/assets/137017155/4e4f1d33-58dc-4dbe-af4c-3741310de70d)
---
> 사용자 및 스타일
> 
![마이페이지](https://github.com/wuuuugi/shopping/assets/137017155/067585b3-24c9-4228-8f44-9cc5345408bd)
![마이페이지_주소록_새 배송지 추가2](https://github.com/wuuuugi/shopping/assets/137017155/d16061f9-19db-4083-a5f7-f11b579fafd8)
![스타일 게시글](https://github.com/wuuuugi/shopping/assets/137017155/8f1ef33e-2120-4ac9-9f6b-f164c6b7a40c)
![스타일메인](https://github.com/wuuuugi/shopping/assets/137017155/830026e4-2ffb-4a39-9b7e-6bd6f1bec2f8)

<br>
<br>
<br>
<br>
