#!/bin/env python

import markdown
import sys

print markdown.markdown(''.join(sys.stdin.readlines()))
