public class Coordinates {
    private int x;
    private int y;
    public Coordinates(int x, int y) { this.x = x; this.y = y; }
    public int getX() { return x; }
    public int getY() { return y; }
    public double distance(Coordinates p) {
        int dx = p.getX() - x;
        int dy = p.getY() - y;
        return Math.sqrt(dx*dx + dy*dy);
    }
    public void translate(int dx, int dy) { x += dx; y += dy; }
    public void scale(int factor, boolean sign) {
        if (sign) { x *= factor; y *= factor; }
        else if (factor != 0) { x /= factor; y /= factor; }
    }
    public String display() { return "X=" + x + " Y=" + y; }
}
