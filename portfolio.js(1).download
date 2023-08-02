var header = document.getElementById("header-elems");
var menuItems = header.getElementsByClassName("icon-container");
const projectContainerEl = document.getElementById("project-container");
const starratingEl = document.getElementById("star-rating");
for (var i = 0; i < menuItems.length; i++) {
  menuItems[i].addEventListener("click", function () {
    var currentItem = document.getElementsByClassName(" active");
    currentItem[0].className = currentItem[0].className.replace("active", "");
    this.className = this.className + " active";
    //console.log(this.id);
    var level = this.id;
    if (level == 1) {
      window.scroll({
        top: 0,
        left: 0,
        behavior: "smooth",
      });
    } else if (level == "2") {
      window.scroll({
        top: level * 300,
        left: 0,
        behavior: "smooth",
      });
    } else if (level == "3") {
      window.scroll({
        top: level * 470,
        left: 0,
        behavior: "smooth",
      });
    } else if (level == "4") {
      window.scroll({
        top: level * 530,
        left: 0,
        behavior: "smooth",
      });
    } else {
      window.scroll({
        top: 3000,
        left: 0,
        behavior: "smooth",
      });
    }
  });
}
// or you can use switch case
// switch (level) {
//     case "1":
//         window.scroll({
//             top: level * 530,
//             left: 0,
//             behavior: "smooth",
//         });
//         break;
//     case "2":
//         window.scroll({
//             top: level * 530,
//             left: 0,
//             behavior: "smooth",
//         });
//         break;
//     case "3":
//         window.scroll({
//             top: level * 530,
//             left: 0,
//             behavior: "smooth",
//         });
//         break;
//     case "4":
//         window.scroll({
//             top: level * 530,
//             left: 0,
//             behavior: "smooth",
//         });
//         break;
//     case "5":
//         window.scroll({
//             top: level * 530,
//             left: 0,
//             behavior: "smooth",
//         });
//         break;
//     }

//var str = "tomorrow is  extra class";
//str = str.replace("tomorrow","today");
//console.log(str);

// for (let i = 1; i <= 3; i++) {
//   projectContainerEl.innerHTML += '<a href="https://github.com"><div class="project-card" id="card${i}"></div></a>`;
// }

// for (let i = 1; i <= 5; i++){
//     starratingEl.innerHTML += '<svg width="18" height="18"viewBox="0 0 18 18"fill="none"xmlns="http://www.w3.org/2000/svg"><path d="M9 13.2448L12.9107 12.2343L14.5446 17.3684L9 13.2448ZM18 6.60873H11.1161L9 0L6.88393 6.60873H0L5.57143 10.7051L3.45535 17.3138L9.02679 13.2175L12.4554 10.7051L18 6.60873Z"fill="#FFB400"/></svg><div class="project-card" id="star${i}"></div>';
// }
