#!/usr/bin/env python3

import markdown
import sys

print(markdown.markdown(''.join(sys.stdin.readlines())))
