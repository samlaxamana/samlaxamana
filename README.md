//  Generated Leanbot Arduino code
//    by Leanbot Blockly Editor 2024-09-05
//    at 2024-09-10 20:56:15

#include <Leanbot.h>

void setup() {
  Leanbot.begin();
}

void loop() {
  LbMotion.runLRrpm(30, 30);
  LbMotion.waitDistanceMm(17.4 * 10);
  LbMotion.runLRrpm(30, -30);
  LbMotion.waitRotationDeg(90);
  LbMotion.runLRrpm(30, 30);
  LbMotion.waitDistanceMm(5.8 * 10);
  LbMotion.runLRrpm(30, -30);
  LbMotion.waitRotationDeg(90);
  LbMotion.runLRrpm(30, 30);
  LbMotion.waitDistanceMm(8.7 * 10);
  LbRGB.clear();
  LbRGB.fillColor(0xff0000, BITMAP(ledO, ledA, ledB, ledC, ledD, ledE, ledF));
  LbRGB.show();
  LbDelay(0.5 * 1000);
  LbRGB.clear();
  LbRGB.fillColor(0xffcc66, BITMAP(ledO, ledA, ledB, ledC, ledD, ledE, ledF));
  LbRGB.show();
  LbDelay(0.5 * 1000);
  LbRGB.clear();
  LbRGB.fillColor(0x33ff33, BITMAP(ledO, ledA, ledB, ledC, ledD, ledE, ledF));
  LbRGB.show();
  LbDelay(0.5 * 1000);
  LbRGB.clear();
  LbRGB.fillColor(0x66cccc, BITMAP(ledO, ledA, ledB, ledC, ledD, ledE, ledF));
  LbRGB.show();
  LbDelay(0.5 * 1000);
  LbRGB.clear();
  LbRGB.fillColor(0x6666cc, BITMAP(ledO, ledA, ledB, ledC, ledD, ledE, ledF));
  LbRGB.show();
  LbDelay(0.5 * 1000);
  LbRGB.clear();
  LbRGB.fillColor(0xffccff, BITMAP(ledO, ledA, ledB, ledC, ledD, ledE, ledF));
  LbRGB.show();
  LbDelay(0.5 * 1000);
  LbRGB.clear();
  LbRGB.fillColor(0xcc33cc, BITMAP(ledO, ledA, ledB, ledC, ledD, ledE, ledF));
  LbRGB.show();
  for (int count = 0; count < 6; count++) {
    LbRGB.fillColor(0xff0000, BITMAP(ledO, ledA, ledB, ledF));
    Leanbot.tone(1500, 500);
    LbDelay(500);
    LbRGB.clear();
    LbRGB.show();
    LbDelay(0.5 * 1000);
    LbRGB.clear();
    LbRGB.fillColor(0x3333ff, BITMAP(ledO, ledC, ledD, ledE));
    Leanbot.tone(1000, 500);
    LbDelay(500);
    LbRGB.show();
  }

  LbMotion.runLRrpm(-30, 30);
  LbMotion.waitRotationDeg(90);
  LbMotion.runLRrpm(30, 30);
  LbMotion.waitDistanceMm(5.8 * 10);
  LbMotion.runLRrpm(30, -30);
  LbMotion.waitRotationDeg(90);
  LbMotion.runLRrpm(30, 30);
  if ((Leanbot.pingCm() < 5)) {
    LbRGB.clear();
    LbRGB.fillColor(0xffff00, BITMAP(ledO, ledA, ledB, ledC, ledD, ledE, ledF));
    LbRGB.show();
  }
  if ((Leanbot.pingCm() < 0.5)) {
    LbMotion.stopAndWait();
    for (int count2 = 0; count2 < 2; count2++) {
      LbRGB.clear();
      LbRGB.fillColor(0xffff00, BITMAP(ledE, ledF));
      LbRGB.show();
      LbDelay(0.75 * 1000);
      LbRGB.clear();
      LbRGB.fillColor(0xffff00, BITMAP(ledO, ledA, ledD));
      LbRGB.show();
      LbDelay(0.75 * 1000);
      LbRGB.clear();
      LbRGB.fillColor(0xffff00, BITMAP(ledB, ledC));
      LbRGB.show();
      LbDelay(0.75 * 1000);
    }

    LbRGB.clear();
    LbRGB.fillColor(0x66ff99, BITMAP(ledO, ledA, ledB, ledC, ledD, ledE, ledF));
    LbRGB.show();
  }
  LbDelay(1 * 1000);
  LbGripper.moveTo(75);
  LbMotion.runLRrpm(30, 30);
  for (int count3 = 0; count3 < 6; count3++) {
    LbRGB.clear();
    LbRGB.fillColor(0xff0000, BITMAP(ledO, ledA, ledB, ledF));
    Leanbot.tone(1500, 500);
    LbDelay(500);
    LbRGB.show();
    LbDelay(0.5 * 1000);
    LbRGB.clear();
    LbRGB.fillColor(0x3333ff, BITMAP(ledO, ledC, ledD, ledE));
    Leanbot.tone(1000, 500);
    LbDelay(500);
    LbRGB.show();
  }


  !false;

  if (false) {
  } else {
    LbRGB.clear();
  }

  switch (i) {
    case false:
  }

}
