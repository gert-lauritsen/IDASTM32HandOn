/*
 * WS2812.h
 *
 *  Created on: May 26, 2024
 *      Author: gert
 */

#ifndef SRC_WS2812_H_
#define SRC_WS2812_H_
#include "stdint.h"
typedef union
{
  struct
  {
    uint8_t b;
    uint8_t r;
    uint8_t g;
  } color;
  uint32_t data;
} PixelRGB_t;

#define WS2812_NUM_PIXELS 40


PixelRGB_t pixel[WS2812_NUM_PIXELS] = {0};

void WS2812_UpdatePixel();


#endif /* SRC_WS2812_H_ */
