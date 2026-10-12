#!/bin/bash

echo "=== Disk Storage Usage ==="
df -h

echo ""
echo "=== Home Directory Size ==="
du -sh ~/*
